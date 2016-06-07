Questo è il file php di funzionamento

<?php
error_reporting(E_ALL ^ E_DEPRECATED);
session_start();

if (isset($_POST['register'])) {
				$Name=$_POST['Name'];
				$EmailR=$_POST['EmailR'];
				$PasswordR=$_POST['PasswordR'];
				$conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
				mysql_select_db('Sql824901_1', $conn) or die(mysql_error());
				mysql_query("SET NAMES utf8");
				$reg= mysql_query ("INSERT INTO utenti(name,email,password) VALUES('$Name','$EmailR','$PasswordR')");
				if ($reg){
				echo '<script type="text/javascript">alert(\'Thank You! You have registered successfully! Please Log In.\');</script>';}
				if (!$reg){ echo '<script type="text/javascript">alert(\'Email already exisits.\');</script>';}
				}
				
if (isset($_POST['stato1']))
   {echo"<script>location='Home.php#joinusd';</script>";}		
if (isset($_POST['stato2']))
   {echo"<script>location='Home.php#joinust';</script>";}	
if (isset($_POST['stato3']))
   {echo"<script>location='Home.php#joinusm';</script>";}	
   
if (isset($_POST['tracciato1']))
   {echo"<script>location='Home.php#joinusd';</script>";}		
if (isset($_POST['tracciato2']))
   {echo"<script>location='Home.php#joinust';</script>";}	
if (isset($_POST['tracciato3']))
   {echo"<script>location='Home.php#joinusm';</script>";}	
   

if (isset($_POST['tappa']))
                      {
					  $stage=$_POST['stage'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $query= "SELECT * FROM stage WHERE city='$stage'" or die(mysql_error());
					  $result=mysql_query($query);
                      $count=mysql_num_rows($result);
				      $riga=mysql_fetch_array($result);
				      $_SESSION["iden"]= $count;
				      $_SESSION["uni"]= $riga [0];
				      $_SESSION["city"]= $riga [1];
				      $_SESSION["country"]= $riga [2];
				      $_SESSION["route"]= $riga [3];
					  $idmappa= $_SESSION["uni"];
					  $query1= "SELECT * FROM url WHERE id='$idmappa'" or die(mysql_error()); 
					  $result1=mysql_query($query1);
                      $count1=mysql_num_rows($result1);
				      $riga1=mysql_fetch_array($result1);
				      $_SESSION["identity"]= $count1;
				      $_SESSION["unif"]= $riga1 [0];
				      $_SESSION["url"]= $riga1 [1];
					  if($count)
				      {echo "<script>location='Stage.php';</script>";}
					  else
					  {echo '<script type="text/javascript">alert(\'no\');</script>';}}

				
if (isset($_POST['sendusp'])) {
	if (($_SESSION["id"]!=0)){
	error_reporting(E_ALL ^ E_DEPRECATED);
	            $mail='photo@europeancyclerelay.eu';
				$oggetto="foto";
				$messaggio1=$_SESSION["city"];
				$messaggio2=$_SESSION['nome'];				
				$photo=$_FILES['photo']['tmp_name'];
				$photo_type=$_FILES['photo']['type'];
				$photo_name=$_FILES['photo']['name'];
				$headers = "";
                $msg = "";			
				$file = fopen($photo,'rb');
                $data = fread($file, filesize($photo));
                fclose($file);
				$data = chunk_split(base64_encode($data));
				$semi_rand = md5(time());
                $mime_boundary = "==Multipart_Boundary_x{$semi_rand}x";
				$headers .= "\nMIME-Version: 1.0\n";
                $headers .= "Content-Type: multipart/mixed;\n";
                $headers .= " boundary=\"{$mime_boundary}\"";
				$msg .= "This is a multi-part message in MIME format.\n\n";
				$msg .= "--{$mime_boundary}\n";
				$msg .= "Content-Type: text/plain; charset=\"iso-8859-1\"\n";
                $msg .= "Content-Transfer-Encoding: 7bit\n\n";
				$msg .= $messaggio1 . "\n\n";
				$msg .= $messaggio2 . "\n\n";
				$msg .= "--{$mime_boundary}\n";
				$msg .= "Content-Disposition: attachment; filename=\"{$photo_name}\"\n";
                $msg .= "Content-Transfer-Encoding: base64\n\n";
                $msg .= $data . "\n\n";
				$msg .= "--{$mime_boundary}--\n";
				if (mail($mail, $oggetto, $msg, $headers))
				{echo '<script type="text/javascript">alert(\'mail inviata.\');</script>';}}	
				else
				{echo '<script type="text/javascript">alert(\'You need to be logged.\');</script>';}
				{echo "<script>location='Stage.php';</script>";}						
				}


if (isset($_POST['send'])) {
				$Email=$_POST['EmailF'];
				$conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
				mysql_select_db('Sql824901_1', $conn) or die(mysql_error());
				mysql_query("SET NAMES utf8");
				$Email = stripslashes($Email);
				$Email = mysql_real_escape_string($Email);
				$query="SELECT * FROM utenti WHERE email='$Email'" or die(mysql_error());
				$result=mysql_query($query);
                $count=mysql_num_rows($result);
				$riga=mysql_fetch_array($result);
				$pass=$riga [3];
				$mail=$riga [2];
				$nome_mittente='European Cycle Relay';
				$mail_mittente='info@europeancyclerelay.eu';
				$mail_headers = "From: " .  $nome_mittente . " <" .  $mail_mittente . ">\r\n";
                $mail_headers .= "Reply-To: " .  $mail_mittente . "\r\n";
                $mail_headers .= "X-Mailer: PHP/" . phpversion();
				$oggetto='Password';
				$messaggio='Your password is: ' .$pass.'';
				if($count) {
				{mail($mail,$oggetto,$messaggio,$mail_headers);}
				{echo '<script type="text/javascript">alert(\'Please check Your email. Thank You\');</script>';}}
				else
				{
                   echo '<script type="text/javascript">alert(\'Invalid Email or Password. Please retry\');</script>';
				   }
			}				

session_unset();
session_destroy();
?>

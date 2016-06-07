Questa è la pagina Stage dove tu arrivi dopo aver scelto dal form e qui ho bisogno dell'id nella url in modo che se condivido la id mi richiama tutti i dati relativi

<!doctype html>
<html class="">
<head>
<link rel="shortcut icon" href="images/favicon.ico"/>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta property="og:type" content="website" />
<meta property="og:title" content="European Cycle Relay" />
<meta property="og:description" content="Find Your own Stage and enjoy us!" />
<meta property="og:image" content="http://www.europeancyclerelay.eu/images/europeancyclerelay.png" />
<meta property="og:url" content="http://www.europeancyclerelay.eu/" />
<title>Stage</title>
<?php 
error_reporting(E_ALL ^ E_DEPRECATED);
include("funzioni.php");
?>
<link href="boilerplate.css" rel="stylesheet" type="text/css">
<link href="style.css" rel="stylesheet" type="text/css">
<script type="text/javascript">
	var _iub = _iub || [];
	_iub.csConfiguration = {
		cookiePolicyId: 908793,
		siteId: 210238,
		lang: "en",
		priorConsent: false
	};
	(function (w, d) {
		var loader = function () { var s = d.createElement("script"), tag = d.getElementsByTagName("script")[0]; s.src = "//cdn.iubenda.com/cookie_solution/beta/iubenda_cs.js"; tag.parentNode.insertBefore(s, tag); };
		if (w.addEventListener) { w.addEventListener("load", loader, false); } else if (w.attachEvent) { w.attachEvent("onload", loader); } else { w.onload = loader; }
	})(window, document);
</script>
<script src="respond.min.js"></script>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js"></script>
<script>
$(document).ready(function (){           
			$("#tomenudesktop").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#top").offset().top
                    }, 2000);
            });
        });

function MM_preloadImages() { //v3.0
  var d=document; if(d.images){ if(!d.MM_p) d.MM_p=new Array();
    var i,j=d.MM_p.length,a=MM_preloadImages.arguments; for(i=0; i<a.length; i++)
    if (a[i].indexOf("#")!=0){ d.MM_p[j]=new Image; d.MM_p[j++].src=a[i];}}
}
</script>
</head>
<body>
<div id="desktop">
<div class="gridContainer clearfix fluid" id="menu">
        <table align="center" width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#666666; color:#ffffff; line-height:0">
  <tr>
    <td width="25%" align="center" nowrap><h5 style="padding-top:1%"><a href="Home.php" id="top">European Cycle Relay</a></h5></td>
    <td width="12.5%" align="center" nowrap><h6><a href="Home.php#joinusd" id="joinus">Join Us</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="Home.php#theprojectd" id="theproject">The project</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="Home.php#aboutusd" id="aboutus">About Us</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="Forum.php" id="forum">Forum</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6>Friends</h6></td>
    <td width="12.5%" align="center" nowrap><h6 id="PastEditions"><a href="PastEditions.php" id="past">Past editions</a></h6></td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="areadesktop">
<table width='100%' border='0' cellspacing='0' cellpadding='0' style="background:#999999; color:#ffffff">
<tr>
<td align="right" style="padding-right:1%"><a href="YourPage.php"><?php
			if (isset($_SESSION["id"]) && ($_SESSION["id"]!=0))
            {echo "<p style='line-height:0; color:#ffffff; padding-right:1%'>".$_SESSION['nome']."</p>";}?></a></td>          
</tr></table>
</div>
<div class="gridContainer clearfix fluid" id="mappadesktop" align="center">
<?php
			if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
            {echo $_SESSION["url"];}
            ?>
</div>
<div class="gridContainer clearfix fluid" id="descriptiondesktop">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td style="line-height:1; padding-left:1%; padding-right:1%"><h3 style="text-align:left; color:#99cc00">
	<?php
			if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
            {echo $_SESSION["city"];}
            ?></h3>
<h5 style="text-align:left; color:#99cc00"><em><?php
			if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
            {echo $_SESSION["country"];}
            ?> - <?php
			if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
            {echo $_SESSION["route"];}
            ?></em></h5>
<p style="text-align:justify; color:#666666">Here You can find a suggested itinerary, however please feel free to choose whether You want to ride the full track or only part of it, but most choose the road more comfortable and safe to go and enjoy it! Check the board below to find other cyclists and share the stage!<br>Do You like this stage? You can choose it and find it on Your personal page, but You need to be logged first, click <label for="modal-5"><strong style="color:#99cc00">here</strong></label> to log in.</p></td>
  </tr>
  <tr><td>&nbsp;</td></tr>
  <tr>
  <td align="center"><form action="" method="post" name="adopt" id="adopt">
  <input type="hidden" id="adopts" required name="adopts" value="<?php
			if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
            {echo $_SESSION["city"];}
            ?>">
  <input type="hidden" id="adoptn" name="adoptn" value="<?php
			if (isset($_SESSION["id"]) && ($_SESSION["id"]!=0))
            {echo $_SESSION["nome"];}
            ?>">
  <input name="adopt" type="submit" id="adopt" form="adopt" formmethod="POST" value="adopt this stage" style="line-height:1.5; vertical-align:bottom; width:20%"></form></td></tr>
  <tr>
  <td>&nbsp;</td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="formdesktop">
  <table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="center" style="background-color:#999999; color:#ffffff"><h3><em>share with us</em></h3></td></tr>
    <tr><td style="line-height:1.2; padding-left:1%; padding-right:1%"><p style="text-align:justify; color:#666666">Write us a message and send it to our dashboard. You can find other cyclists to share a beatifull day cycling a stage!<br>Have You done this stage? So leave a comment and uppload a photo to let other cyclists know how amazing is!<br>But you need to be logged first, click <label for="modal-5"><strong style="color:#99cc00">here</strong></label> to log in.</p></td>
  </tr>  
  <tr>
    <td align="center"><h5><form action="" method="post" name="sendusm" id="sendusm">
    <input name="message" type="text" required id="message" placeholder="Message" style="border:0; background-color:#cccccc; color:#666666;" size="34%" maxlength="500"></br></br>
    <input name="sendusm" type="submit" id="sendusm" formmethod="POST" style="line-height:1.5; vertical-align:bottom; width:10%" title="sendusm" value="send"></form></h5></td>
  </tr>
  <tr>
    <td align="center"><h5><form action="" method="post" name="sendusp" id="sendusp" enctype="multipart/form-data">
    <input name="photo" type="file" multiple required id="photo" style="border:0; background-color:#cccccc; color:#666666"></br></br>
    <input name="sendusp" type="submit" id="sendusp" formmethod="POST" style="line-height:1.5; vertical-align:bottom; width:10%" title="sendusp" value="send"></form></h5></td>
  </tr>
  <tr>
  <td style="line-height:1.2; padding-left:1%; padding-right:1%"><p style="text-align:justify; color:#666666">The photos will send to us in order to be sure that are not inappropriate and then will be upload. We could not do the same for the messages, so if You read something that hurt You please send us a notice writing us a mail with the Stage information (starting and ending Cities), Name of the user and related message.</p></td>
  </tr>
</table>
<input class="modal-state" id="modal-5" type="checkbox" />
<div class="modal">
  <label class="modal__bg" for="modal-5"></label>
  <div class="modal__inner5">
    <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center"><h5><form action="" method="post" name="login2d" id="login2d"><input name="EmailL" type="email" required id="EmailL" placeholder="Email"  style="border:0; opacity:0.7" size="30%"></br></br><input name="PasswordL" type="password" required id="PasswordL" placeholder="Password"  style="border:0; opacity:0.7" size="30%"></br></br><input name="login" type="submit" id="login" formmethod="POST" value="log in" style="line-height:1.5; vertical-align:bottom; width:20%"><label for="modal-2"><p style="color:#ffffff">Not Registered yet?</p></label><label for="modal-3"><p style="color:#ffffff">Forgot Password?</p></label></form></h5></td>
  </tr>
</table>
  </div>
</div>
<input class="modal-state" id="modal-2" type="checkbox" />
<div class="modal">
  <label class="modal__bg" for="modal-2"></label>
  <div class="modal__inner2">
    <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">  
  <tr>
    <td align="center" style="color:#ffffff"><h5><form action="" method="post" name="register" id="register">
    <input name="Name" type="text" required id="Name" placeholder="Name"  style="border:0" size="30%"></br></br><input name="EmailR" type="email" required id="EmailR" placeholder="Email"  style="border:0" size="30%"></br></br><input name="PasswordR" type="password" required id="PasswordR" placeholder="Password"  style="border:0" size="30%"></h5>
      <p>Accept our <strong><a href="https://www.iubenda.com/privacy-policy/908793" target="new" style="color:#99cc00">Privacy Policy</a></strong>
<input type="checkbox" required style="border:0">
      </p><h5 align="center"><input name="register" type="submit" id="register" formmethod="POST" style="line-height:1.5; vertical-align:bottom; width:20%" title="register" value="register"></h5></form></td>
  </tr>
</table>
  </div>
</div>
<input class="modal-state" id="modal-3" type="checkbox" />
<div class="modal">
  <label class="modal__bg" for="modal-3"></label>
  <div class="modal__inner3">
    <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">  
  <tr>
    <td align="center" style="color:#ffffff"><h5><form action="" method="post" name="forgot" id="forgot">
    <input name="EmailF" type="email" required id="EmailF" placeholder="Email"  style="border:0" size="30%"></h5><h5 align="center"><input name="send" type="submit" id="send" formmethod="POST" style="line-height:1.5; vertical-align:bottom; width:20%" title="send" value="send"></h5></form></td>
  </tr>
</table>
  </div>
</div>

</div>
<div class="gridContainer clearfix fluid" id="gallerydesktop1">
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" style="text-align:center">
  <tr>
    <td align="center" style="background-color:#999999; color:#ffffff"><h3><em>latests photos</em></h3></td>
  </tr></table></div>
  <form><div class="gridContainer clearfix fluid" id="gallerydesktop2" align="center" style="background-color: #cccccc">
<?php
					  if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
					  $stage=$_SESSION["city"];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_3', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $query= mysql_query("SELECT * FROM foto WHERE stage='$stage' ORDER BY data DESC") or die(mysql_error());
					  while ($dato = mysql_fetch_array($query))
					  {
					  echo "<div class='caption'><img src='" .$dato['photo']. "'/><span><p style='line-height:1; text-align:center'><label for='modal-4'><strong>" .$dato['name']. "</strong></label></p></span></div>";}
					  ?>
</div>
<input class="modal-state" id="modal-4" type="checkbox" />
<div class="modal">
  <label class="modal__bg" for="modal-4"></label>
  <div class="modal__inner4" align="center">
    <?php
					  if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
					  $stage=$_SESSION["city"];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_3', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $query= mysql_query("SELECT * FROM foto WHERE stage='$stage' ORDER BY data DESC") or die(mysql_error());
					  while ($dato = mysql_fetch_array($query))
					  {
					  echo "<div class='caption' style='loat:left'><img src='" .$dato['photol']. "'/><span><p style='line-height:1; text-align:center'><strong>" .$dato['name']. "</strong></p></span></div>";
					  }
					  ?>
  </div>
</div>
<div class="gridContainer clearfix fluid" id="messagesdesktop">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="center" style="background-color:#999999; color:#ffffff"><h3><em>recents messages</em></h3></td>
  </tr>
  <tr>
    <td style="padding-left:1%; padding-right:1%">    
    <?php
					  if (isset($_SESSION["iden"]) && ($_SESSION["iden"]!=0))
					  $stage=$_SESSION["city"];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_3', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $query= mysql_query("SELECT * FROM messaggio WHERE stage='$stage' ORDER BY data DESC") or die(mysql_error());
					  while ($dato = mysql_fetch_array($query)){
					  echo "<h5 style='color:#99cc00; line-height:0'>" .$dato['name']. "</h5><p style='text-align:justify; line-height:1.2; background-color:#cccccc; color: #666666'>" .$dato['message']. "</p>";
					  }
					  ?></td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="footer">
        <table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#666666; color:#ffffff">
  <tr>
    <td align="center"><h5>info@europeancyclerelay.eu</h5></td>
  </tr>
  <td align="center"><p><a href="https://www.iubenda.com/privacy-policy/908793" target="new" style="color:#99cc00"><strong>Privacy Policy</strong></a></p></td>
  </tr>
</table>
</div>
<div id="top" style="position: fixed; bottom: 5px; right: 15px; cursor: pointer;"><a href="#top" id="tomenudesktop"><p style="line-height: 1.2; padding:inherit; text-align: justify"><img src="images/top.png"></p></a>
</div>
</div>
</body>
</html>

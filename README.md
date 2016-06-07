Questa è la home la metto tutta dimmi te se togliere qualcosa

<!doctype html>
<html class="">
<head>
<link rel="shortcut icon" href="images/favicon.ico"/>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta property="og:type" content="website" />
<meta property="og:title" content="European Cycle Relay" />
<meta property="og:description" content="Find Your own Stage and enjoy us!" />
<meta property="og:image" content="http://www.europeancyclerelay.eu/images/share.png" />
<meta property="og:url" content="http://www.europeancyclerelay.eu/" />
<title>European Cycle Relay</title>
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
            $("#tojoinusd").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#joinusd").offset().top
                    }, 2000);
            });
			$("#joinusad").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#joinusd").offset().top
                    }, 2000);
            });
			$("#tojoinust").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#joinust").offset().top
                    }, 2000);
            });
			$("#joinusat").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#joinust").offset().top
                    }, 2000);
            });
			$("#tojoinusm").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#joinusm").offset().top
                    }, 2000);
            });
			$("#joinusam").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#joinusm").offset().top
                    }, 2000);
            });
			$("#totheproject").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#theprojectd").offset().top
                    }, 2000);
            });
			 $("#toaboutus").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#aboutusd").offset().top
                    }, 2000);
            });
			$("#tomenu").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#top").offset().top
                    }, 2000);
            });
			$("#tofriendsd").click(function (){
                    $('html, body').animate({
                        scrollTop: $("#friendsd").offset().top
                    }, 2000);
            });
        });

function MM_preloadImages() { //v3.0
  var d=document; if(d.images){ if(!d.MM_p) d.MM_p=new Array();
    var i,j=d.MM_p.length,a=MM_preloadImages.arguments; for(i=0; i<a.length; i++)
    if (a[i].indexOf("#")!=0){ d.MM_p[j]=new Image; d.MM_p[j++].src=a[i];}}
}
function MM_swapImgRestore() { //v3.0
  var i,x,a=document.MM_sr; for(i=0;a&&i<a.length&&(x=a[i])&&x.oSrc;i++) x.src=x.oSrc;
}
function MM_findObj(n, d) { //v4.01
  var p,i,x;  if(!d) d=document; if((p=n.indexOf("?"))>0&&parent.frames.length) {
    d=parent.frames[n.substring(p+1)].document; n=n.substring(0,p);}
  if(!(x=d[n])&&d.all) x=d.all[n]; for (i=0;!x&&i<d.forms.length;i++) x=d.forms[i][n];
  for(i=0;!x&&d.layers&&i<d.layers.length;i++) x=MM_findObj(n,d.layers[i].document);
  if(!x && d.getElementById) x=d.getElementById(n); return x;
}

function MM_swapImage() { //v3.0
  var i,j=0,x,a=MM_swapImage.arguments; document.MM_sr=new Array; for(i=0;i<(a.length-2);i+=3)
   if ((x=MM_findObj(a[i]))!=null){document.MM_sr[j++]=x; if(!x.oSrc) x.oSrc=x.src; x.src=a[i+2];}
}
</script>
</head>
<body>
<div id="desktop">
<div class="gridContainer clearfix fluid" id="menu">
        <table align="center" width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#666666; color:#ffffff; line-height:0">
  <tr>
    <td width="25%" align="center" nowrap><h5 style="padding-top:1%"><a href="Home.php" id="top">European Cycle Relay</a></h5></td>
    <td width="12.5%" align="center" nowrap><h6><a href="#joinusd" id="tojoinusd">Join Us</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="#theprojectd" id="totheproject">The project</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="#aboutusd" id="toaboutus">About Us</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="Forum.php" id="forum">Forum</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="#friendsd" id="tofriendsd">Friends</a></h6></td>
    <td width="12.5%" align="center" nowrap><h6><a href="PastEditions.php">Past editions</a></h6></td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="area">
<table width='100%' border='0' cellspacing='0' cellpadding='0' style="background:#999999; color:#ffffff">
<tr>
<td align="right" style="padding-right:1%"><a href="YourPage.php"><?php
			if (isset($_SESSION["id"]) && ($_SESSION["id"]!=0))
            {echo "<p style='line-height:0; color:#ffffff; padding-right:1%'>".$_SESSION['nome']."</p>";}?></a></td>         
</tr></table>
</div>
<div class="gridContainer clearfix fluid" id="copertina">

<table width="100%" border="0" cellspacing="0" cellpadding="0" background="images/Copertina.png" style="background-position:center; background-repeat:no-repeat; background-color:#999999">
  <tr>
    <td align="center" style="padding-top:3%; padding-bottom:1%"><img src="images/Logo.png" width="250"></td>
  </tr>
  <tr>
    <td align="center" valign="top" style="color:#ffffff; line-height:0"><h1><em>Join the longest Cycle Relay accross Europe!</em></h1></td>
  </tr>
  <tr>
    <td><table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
  <tr>  
    <td width="40%"></td>
    <td align="center"><p style="background-color:#99cc00; color:#ffffff; line-height:1.5; font-size: 1em"><a href="#joinusd" id="joinusad"><strong>adopt a stage</strong></a></p></td>
    <td width="40%"></td>
  </tr>
</table>    
  </tr>
  <tr>
    <td><table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
  <tr>
    <td width="40%"></td>
    <td width="9%" align="center"><p style="background-color:#99cc00; color:#ffffff; line-height:1.5; font-size: 1em"><label for="modal-1"><strong>log in</strong></label></p></td>
    <td width="2%"></td>
    <td width="9%" align="center"><p style="background-color:#99cc00; color:#ffffff; line-height:1.5; font-size: 1em"><label for="modal-2"><strong>register</strong></label></p></td>
    <td width="40%"></td>
  </tr>
</table>
</td>
  </tr>
  <tr><td><h1>&nbsp;</h1></td></tr>
</table>
<input class="modal-state" id="modal-1" type="checkbox" />
<div class="modal">
  <label class="modal__bg" for="modal-1"></label>
  <div class="modal__inner1">
    <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center"><h5><form action="" method="post" name="login1" id="login1"><input name="EmailL" type="email" required id="EmailL" placeholder="Email"  style="border:0; opacity:0.7" size="30%"></br></br><input name="PasswordL" type="password" required id="PasswordL" placeholder="Password"  style="border:0; opacity:0.7" size="30%"></br></br><input name="login" type="submit" id="login" formmethod="POST" value="log in" style="line-height:1.5; vertical-align:bottom; width:10%"><label for="modal-3"><p style="color:#ffffff">Forgot Password?</p></label></form></h5></td>
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
    <td align="center" style="color:#ffffff"><h5><form action="" method="post" name="register1" id="register1">
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
    <td align="center" style="color:#ffffff"><h5><form action="" method="post" name="forgot1" id="forgot1">
    <input name="EmailF" type="email" required id="EmailF" placeholder="Email"  style="border:0" size="30%"></h5><h5 align="center"><input name="send" type="submit" id="send" formmethod="POST" style="line-height:1.5; vertical-align:bottom; width:20%" title="send" value="send"></h5></form></td>
  </tr>
</table>
  </div>
</div>
</div> 
<div class="gridContainer clearfix fluid" id="gallery1">
<table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#98cbcb">
  <tr>
    <td align="center" style="background-color:#999999; color:#ffffff"><h3><em><a href="Forum.php">forum</a></em></h3></td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="gallery2" align="center" style="background-color:#cccccc">
<?php
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_3', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $query= mysql_query("SELECT * FROM foto ORDER BY data DESC LIMIT 4") or die(mysql_error());
					  while ($dato = mysql_fetch_array($query))
					  {
					  echo "<div class='caption'><img src='" .$dato['photo']. "'/><span><form action='' method='post'><p><input name='tappa' type='submit' id='tappa' formmethod='POST' style='background:#ffffff; color:#99cc00; line-height:1' value='" .$dato['name']. "'></p><input type='hidden' id='stage' name='stage' value='".$dato['stage']."'></form></span></div>";}
					  ?>
</div>
<div class="gridContainer clearfix fluid" id="joinusd">
<table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#98cbcb">
  <tr>
    <td width="50%" style="background-color:#98cbcb"><table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding-left:3%; color:#ffffff"><h3><em>find your stage and join us!</em></h3></td>
  </tr>
  <tr>
    <td style="padding-left:3%; color:#ffffff"><h5>1) Select a Country: <?php
                      if (isset($_POST['stato1']))
                      {
					  $country=$_POST['country'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT country FROM joinus WHERE country='$country'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "<em style='color:#99cc00; background-color:#ffffff; padding:1%; border-radius:10px'>" .$dato['country']. "</em>";}
					  }
					  elseif (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT country FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "<em style='color:#99cc00; background-color:#ffffff; padding:1%; border-radius:10px'>" .$dato['country']. "</em>";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?></h5></td>
  </tr>
  <tr>
    <td style="padding-left:3%"><p><form action="" method="post" name="stato1" id="stato1">
    <select name="country" style="width:80%" id="country"><option></option><option>Bălgarija</option><option>Belarus</option><option>Belgique</option><option>Bosna i Hercegovina</option><option>Česká republika</option><option>Crna Gora</option><option>Cyprus</option><option>Danmark</option><option>Deutschland</option><option>Eesti</option><option>España</option><option>France</option><option>Hellas</option><option>Hrvatska</option><option>Ireland</option><option>Italia</option><option>Latvija</option><option>Lietuva</option><option>Luxembourg</option><option>Magyarország</option><option>Makedonija</option><option>Malta</option><option>Nederland</option><option>Norge</option><option>Österreich</option><option>Polska</option><option>Portugal</option><option>România</option><option>Rossijskaja Federacija</option><option>Shqipëria</option><option>Slovenija</option><option>Slovensko</option><option>Srbija</option><option>Suisse</option><option>Suomi</option><option>Sverige</option><option>Ukrajina</option><option>United Kingdom</option>
    </select><input name="stato1" type="submit" id="stato1" formmethod="POST" value="ok" style="line-height:0.9; vertical-align:bottom"></form></p></td>
  </tr>
  <tr>
    <td style="padding-left:3%; color:#ffffff"><h5>2) Select a Route: <em style="color:#99cc00"><?php
                      if (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT route FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "<em style='color:#99cc00; background-color:#ffffff; padding:1%; border-radius:10px'>" .$dato['route']. "</em>";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?></em></h5></td>
  </tr>
  <tr>
    <td style="padding-left:3%"><p><form action="" method="post" name="tracciato1" id="tracciato1">
    <input type="hidden" value="<?php
                      if (isset($_POST['stato1']))
                      {
					  $country=$_POST['country'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT country FROM joinus WHERE country='$country'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "" .$dato['country']. "";}
					  }
					  elseif (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT country FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "" .$dato['country']. "";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?>" id="country2" name="country2">
    <select name="route" style="width:80%" id="route"><option></option><?php
                      if (isset($_POST['stato1']))
                      {
					  $country=$_POST['country'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT route FROM joinus WHERE country='$country'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "<option>" .$dato['route']. "</option>";}
					  }
					  elseif (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT route FROM joinus WHERE country='$country'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "<option>" .$dato['route']. "</option>";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?></select><input name="tracciato1" type="submit" id="tracciato1" formmethod="POST" value="ok" style="line-height:0.9; vertical-align:bottom"></form></p></td>
  </tr>
  <tr>
    <td style="padding-left:3%; color:#ffffff"><h5>3) Choose a Stage:</h5></td>
  </tr>
  <tr>
    <td style="padding-left:3%"><form action="" method="post" name="tappa1" id="tappa1">
    <input type="hidden" value="<?php
                      if (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT country FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "" .$dato['country']. "";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?>" id="country3" name="country3">
                <input type="hidden" value="<?php
                      if (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT route FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "" .$dato['route']. "";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?>" id="route2" name="route2">
    <select name="stage" style="width:80%" id="stage"><option></option><?php
    if (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT stage FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "<option>" .$dato['stage']. "</option>";}
					  }
					  else
					  {echo '&nbsp;';}
					  ?></select><input name="tappa" type="submit" id="tappa" formmethod="POST" style="line-height:0.9; vertical-align:bottom" value="ok"></form></p></td>
  </tr>
</table>
</td><td width="50%" align="right"><img src="<?php
                      if (isset($_POST['stato1']))
                      {
					  $country=$_POST['country'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT img FROM joinus WHERE country='$country'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "" .$dato['img']. "";}
					  }
					  elseif (isset($_POST['tracciato1']))
                      {
					  $country=$_POST['country2'];
					  $route=$_POST['route'];
					  error_reporting(E_ALL ^ E_DEPRECATED);
                      $conn= mysql_connect('62.149.150.229','Sql824901','7663320x3z') or die(mysql_error());
                      mysql_select_db('Sql824901_2', $conn) or die(mysql_error());					  
					  mysql_query("SET NAMES utf8");
                      $res= mysql_query("SELECT DISTINCT img2 FROM joinus WHERE country='$country' and route='$route'") or die(mysql_error());
					  while ($dato = mysql_fetch_array($res))
					  {echo "" .$dato['img2']. "";}
					  }
					  else
					  {echo "images/map/Map.png";}
					  ?>">
                     </td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="theprojectd">
<table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#cccccc">
  <tr>
    <td style="line-height:1; padding-left:1%; padding-right:1%"><h4 style="text-align:center; color:#99cc00">How</h4>
    <p style="text-align:justify; color:#ffffff">It's very simple! First select a Country, then select one of the Routes and finally choose a Stage. You'll see then all the details on the Stage, photos and comments left by other cyclists and You can leave Yous. Enjoy Your Stage and of course don't forget to let us know that You did it and send us a picture!</p></td>
  </tr>
  </table>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td width="50%"><table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td style="line-height:1; padding-left:1.5%; padding-right:1.5%"><h4 style="text-align:center; color:#99cc00">What</h4>
    <p style="text-align:justify; color:#666666">The European Cycle Relay is a non-competitive cycling relay that will travel across Europe through 15 routes and 38 countries, at a pace of 70 km per day, adding up to more than 70,000 km!</p></td>
  </tr>
  <tr>
    <td style="line-height:1; padding-left:1.5%; padding-right:1.5%"><h4 style="text-align:center; color:#99cc00">When</h4><p style="text-align:justify; color:#666666">Why having a starting date and an ending one? We have decided that the Home edition will end at the end of the year, but we like to start it on May 9th, <a href="https://en.wikipedia.org/wiki/Europe_Day" target="new" style="color:#99cc00"><strong>Europe Day</strong></a>. So You have a lot of time to cycle your preferred stage.</p></td>
  </tr>
  <tr>
    <td style="line-height:1; padding-left:1.5%; padding-right:1.5%"><h4 style="text-align:center; color:#99cc00">Who</h4>
    <p style="text-align:justify; color:#666666">Anyone. We believe 70 km a day is a distance that can be covered by everyone. You can attend alone, with Your family or in a group, knowing that you are joining other cyclists  along the various routes.</p></td>
  </tr>
</table>
</td>
    <td width="50%"><table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td style="line-height:1; padding-left:1.5%; padding-right:1.5%"><h4 style="text-align:center; color:#99cc00">Why</h4><p style="text-align:justify; color:#666666">Because we love riding our bikes. Because we believe that bikes are a symbol of sustainability. Because we believe that anyone can cycle for 70 km, and even those who don't cycle much. Because we want to be part of a broad-minded, heterogeneous group of people, each doing their bit of the track, carrying a message of unity across Europe.</p></td>
  </tr>
  <tr>
    <td style="line-height:1; padding-left:1.5%; padding-right:1.5%"><h4 style="text-align:center; color:#99cc00">Where</h4>
    <p style="text-align:justify; color:#666666">The tracks, cutting across the whole of Europe, are based on the eurovelo tracks 1 to 17. For each track, You’ll find an indication of where to start and where to end, however please feel free to choose whether You want to ride the full track or only part of it. Also, although we’ll provide a suggested itinerary, but most choose the road more comfortable and safe to go and enjoy it!T</p></td>
  </tr>
</table>
</td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="friendsd">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="center" style="background-color:#999999; color:#ffffff"><h3><em>friends</em></h3></td>
  </tr>
  <tr>
  <td style="line-height:1; padding-left:1%; padding-right:1%"><p style="text-align:justify; color:#666666">Here You can find the link to some of our friends' projects. Find out more about their activities.</p></td>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td width="25%" align="center">&nbsp;</td>
  </tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td width="4%" align="center">&nbsp;</td> 
    <td width="20%" align="center">&nbsp;</td>
    <td width="4%" align="center">&nbsp;</td>
    <td width="20%" align="center"><a href="http://www.biroto.eu/" target="new"><img src="images/biroto.png" alt=""></a></td>
    <td width="4%" align="center">&nbsp;</td>
    <td width="20%" align="center"><a href="http://smartatletic.ro/" target="new"><img src="images/smart-atletic.png" alt=""></a></td>
    <td width="4%" align="center">&nbsp;</td>
    <td width="20%" align="center">&nbsp;</td>
    <td width="4%" align="center">&nbsp;</td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="aboutusd">
<table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#cccccc">
  <tr>
    <td style="line-height:1; padding-left:1%; padding-right:1%"><h4 style="text-align:left; color:#99cc00">About Us</h4>
    <p style="text-align:justify; color:#ffffff">The project European Cycle Relay is a socio-cultural sport event that started in August 2014. It's aim is to promote and raise awareness in Europe and beyond of the use of cycles as sustainable means of transport and to reduce the socio-cultural barriers between European countries. The routes are based on the <a href="http://www.eurovelo.org/" target="new" style="color:#99cc00"><strong>EuroVelo</strong></a> routes identified by the <a href="https://ecf.com/" target="new" style="color:#99cc00"><strong>ECF (European Cyclists’ Federation)</strong></a>. However the individual stages have been developed by our team. The European Cycle Relay has received no funding and is a not-for-profit project.</p></td>
  </tr>
  <tr>
  <td style="line-height:1; padding-left:1%; padding-right:1%"><p style="text-align:justify; color:#ffffff"><a href="http://creativecommons.org/licenses/by-nc-nd/4.0/" target="_new" rel="license"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a></br>European Cycle Relay by is licensed under a <a href="http://creativecommons.org/licenses/by-nc-nd/4.0/" target="new" rel="license">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.</p></td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="social">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td style="line-height:1; padding-left:1%; padding-right:1%"><h4 style="text-align:center; color:#99cc00">Follow Us</h4></td>
  </tr>
  <tr>
    <td><table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr align="center">
    <td width="37.5%">&nbsp;</td>
    <td width="5%"><a href="http://www.facebook.com/europeancyclerelay" target="new"><img src="images/Facebook.png";></a></td>
    <td width="5%">&nbsp;</td>
    <td width="5%"><a href="https://instagram.com/europeancyclerelay/" target="new"><img src="images/Instagram.png";></a></td>
    <td width="5%">&nbsp;</td>
    <td width="5%"><a href="https://twitter.com/EuroCycleRelay" target="new"><img src="images/Twitter.png";></a></td>
    <td width="37.5%">&nbsp;</td>
  </tr>
</table>
</td>
  </tr>
  <tr>
    <td><h5>&nbsp;</h5></td>
  </tr>
</table>
</div>
<div class="gridContainer clearfix fluid" id="footer">
        <table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color:#666666; color:#ffffff">
  <tr>
    <td align="center"><h5>info@europeancyclerelay.eu</h5></td>
  </tr>
  <tr>
  <td align="center"><p><a href="https://www.iubenda.com/privacy-policy/908793" target="new" style="color:#99cc00"><strong>Privacy Policy</strong></a></p></td>
  </tr>
</table>
</div>
<div id="top" style="position: fixed; bottom: 5px; right: 15px; cursor: pointer;"><a href="#top" id="tomenu"><p style="line-height: 1.2; padding:inherit; text-align: justify"><img src="images/top.png"></p></a></div>
</div>
</body>
</html>

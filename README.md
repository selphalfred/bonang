
{
	"id": "com.webos.app.daily-test",
	"title": "Daily Motion",
	"vendor": "Suaji",
	"type": "web",
	"version": "0.0.1",
	"main": "index.html",
	"icon": "icon.png",
	"iconColor":"#E42E28",
	"uiRevision": 2
}


<!DOCTYPE html>
<html>
	<head>
		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
		<title>Redirect URL</title>
		<!-- -->
		<meta http-equiv="Content-Type" content="text/html; charset=utf8"/>
		<meta name="apple-mobile-web-app-capable" content="yes"/>
		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no"/>
	</head>
	<body>
		
	<script src="https://api.dmcdn.net/all.js"></script>
	<div id="player"></div>
	<script>
	var player = DM.player(document.getElementById("player"), {
    video: "x6sun5v",
    width: "100%",
    height: "100%",
    autoplay: true,
	});
	</script>
		
	</body>
</html>


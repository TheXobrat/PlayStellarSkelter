<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Stellar Sketler</title>
    <script src="Build/UnityLoader.js"></script>
    <script>
      UnityLoader.instantiate("unityContainer", "Build/PlayStellarSkelter.json");
    </script>
	<style>
		body { 
			background: #222; 
			margin: 0; 
			padding: 0; 
			max-height: 1080px; 
			overflow: hidden; 
		}
		h1 { display: none; }
		.my-5 { 
			transform: rotate(90deg); 
			width: 0; 
			margin-top: -50% !important; 
		}
	</style>
  </head>
  <body>
    <div id="unityContainer" style="width: 1080px; height: 1920px; margin: auto"></div>
  </body>
</html>

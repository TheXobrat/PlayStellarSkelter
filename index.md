<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Stellar Sketler</title>
    <script src="Build/UnityLoader.js"></script>
    <script>
      UnityLoader.instantiate("unityContainer", "Build/PlayStellarSkelter.json");
    </script>
	<script>
		let container = document.getElementsByTagName("body")[0];

		document.addEventListener("onkeydown", function(e){ 
			if (e.which == 70 || e.keyCode == 70) {
				container.classList.toggle("rotate");
			}
		});
	</script>
	<style>
		body { 
			background: #222; 
			margin: 0; margin-top: -29.6%
			padding: 0; 
			transform: scale(0.563);
			overflow: hidden; 
		}
			body.rotate { 
				margin-top: -50%;
				transform: scale(1) rotate(90deg); 
			}
				body.rotate .my-5 { width: 0; }
		h1 { display: none; }
		.my-5 { 
			margin-top: 0 !important; margin-bottom: 0 !important;
			padding: 0 !important;
		}
	</style>
  </head>
  <body>
    <div id="unityContainer" style="width: 1080px; height: 1920px; margin: auto"></div>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title>Fatimazahra Elmakhloufi</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
      <style>
      * {
        box-sizing:border-box;
        margin: 2;
        padding: 2;
      }
      body {
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 18px;
      }
      h1 {
        font-size: 2em;
        margin-bottom: 1em;
      }
      h2 {
        font-size: 2em;
      }
      .section {
        width: 31%;
        margin: 1%;
        float: left;
        padding: 2em;
        border: 1px solid black;
        background-color: #7d7d7d;
        position: relative;
      }
      .section h2 {
        position: absolute;
        top: 0;
        right: 0;
        background-color: #ffd6b7;
        color: #000000;
        font-size: 75%;
        width: 25%;
        padding: 1em;
        margin: 0;
        border: 1px solid black;
      }
      .section:nth-child(2) h2 {
        background-color: #ffa5cf;
        color: #000000;
        border: 1px solid black;
      }
      .section:nth-child(3) h2 {
        background-color: #ff0000;
        color: #ffffff;
        border: 1px solid black;
      }
      @media screen and (max-width: 991px) and (min-width: 768px) {
        .section {
          width: 50%;
          float: left;
        }
        .section:nth-child(3) {
          width: 100%;
          float: right;
        }
      }
      @media screen and (max-width: 767px) {
        .section {
          width: 100%;
          float: none;
        }
      }
    </style>
  </head>
  <body>
    <center>
        <h1>Our Menu</h1>
    </center>
    <div class="section">
        <center>
            <h2>Chicken</h2>
        </center>
        <p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <div class="section">
        <center>
            <h2>Beef</h2>
        </center>
        <p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <div class="section">
        <center>
            <h2>Sushi</h2>
        </center>
        <p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
  <!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>
</html>

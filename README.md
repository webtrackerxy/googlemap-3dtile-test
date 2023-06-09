# googlemap-3dtile-test

https://developers.google.com/maps/documentation/tile/3d-tiles-overview

Google offers 3D Tiles for next-generation visualization use cases. However, the resources on the official Google website are limited. Cesium has a portal called Sandcastle to test and experience your code with 3D Tiles, requiring just a browser.

I copied some of the code from the official Google website to the Sandcastle portal to demonstrate how easy it is to test different kinds of functions.

Steps:

1. This demo uses Map Tiles, Google Place and Elevation APIs. You need to set up a Google Map service and an API key. You need a project with a billing account, and make the APIs enabled. To learn more, see Setup in <a href="https://developers.google.com/maps/documentation/tile/cloud-setup">Cloud Console</a>.

2. Open the Sandcastle website in a browser that supports WebGL, e.g., Chrome. https://sandcastle.cesium.com/?src=3D%20Tiles%20Formats.html&label=3D%20Tiles

3. Open sandcastle_js.js, replace the api_key with your own. Copy and paste the code to replace the content in the JavaScript code section, while copying html_css.html to replace the HTML body and CSS. Click the "Run (F8)" button at the top of the menu bar.

4. Enter the place name in the place text box (e.g., London), it will guide you to the place. Enjoy playing with the 3D map! When you mouse over a feature, it will be highlighted. Checking the 'Elevation' checkbox will show you the height of the clicked point. You can explore and extend the functions.

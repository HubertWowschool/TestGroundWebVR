# TestGroundWebVR

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>360&deg; Image Gallery</title>
    <meta name="description" content="360&deg; Image Gallery - A-Frame">
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-environment-component/dist/aframe-environment-component.min.js"></script>
  </head>
  <body> <img id="texture" src="texture.png">
    <a-scene>
          <a-box src="https://i.imgur.com/mYmmbrp.jpg" position="0 2 -5" rotation="0 45 45" scale="2 2 2"></a-box>

  <a-sky color="#222"></a-sky>
        <a-entity id="box" position="1 1 -2" geometry="primitive: box" material="color: red"></a-entity>
          <a-box color="red" position="10 2 -5" rotation="0 45 45" scale="2 2 2"></a-box>

  <!-- Out of the box environment! -->
  <a-entity environment="preset: forest; dressingAmount: 500"></a-entity>
    <a-assets>
 
</a-assets>
        <a-box src="#texture"></a-box>
    </a-scene>
  </body>
</html>

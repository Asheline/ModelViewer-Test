# ModelViewer-Test
Test to display a free 3D model from Sketchfab on the web (VSC, Live Server Expansion.)

You only need an HTML-code and a few assets for this code to work on the web.
(model-viewer is supported on the last two major versions of all evergreen desktop and mobile browsers, plus the last two versions of Safari (on MacOS and iOS).)
  
  HTML-code:
  
  ```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Testi</title>
    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
    <style>
        model-viewer{
            width: 1920px;
            height: 1000px;
            margin: 0 auto;
        }

    </style>
</head>
<body>
    <model-viewer src="assets/scene.gltf" camera-controls auto-rotate ar ios-src="assets/Low_Poly_Lake_Scene.usdz"></model-viewer>
</body>
</html>

This work is based on "Low Poly Lake Scene" (https://sketchfab.com/3d-models/low-poly-lake-scene-5fa5d2f996ef472fa41baafe79f64ec2) by EdwinRC (https://sketchfab.com/Edwin3D) licensed under CC-BY-4.0 (http://creativecommons.org/licenses/by/4.0/)

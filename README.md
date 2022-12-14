# AR.js examples

Code for setting up augmented reality (AR) using AR.js. Examples include using a custom marker, displaying a custom 3D model (using glTF files) and AR based on location.

Live at https://alvcwy.github.io/ar-js/

### To run:
- Locally: run with http-server
- Online: host on Github Pages/Glitch (https://glitch.com/dashboard)
- Turn off dark mode to display camera

## TODO:
- Some sort of onclick event for objects in AR
    - Play sound on click?
- Turn debug mode off when deploying and disable VR mode (a-scene, set attribute vr-mode-ui="enabled: false")

- Loading custom models can crash browser and device on iPhone SE 2 (animated Naruto model size too large) (doesn't crash on Xiaomi Poco X3 Pro)


### Done:
- Use custom marker
- Use custom model
- Use custom animated model
- Display image in AR (use a-image)
- Display text in AR (can display instructions) (use a-text)
- Use location-based AR


## Links
### Tutorial for markers:
- https://medium.com/@fauziali/creating-web-based-augmented-reality-with-just-10-lines-of-html-code-for-beginners-ar-js-d62ef596eab

### Custom marker generator:
- https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html

### Downloading pre-made 3D models to display in AR:
- https://sketchfab.com/

### Preview GLTF models:
- https://gltf-viewer.donmccurdy.com/

### Content delivery networks (CDN) to serve custom 3D models:
- https://raw.githack.com/
- https://www.jsdelivr.com/?docs=gh 

### Animating 3D models:
- https://aframe.io/docs/1.3.0/components/gltf-model.html

### Automatically updating AR to use current location:
- https://stackoverflow.com/questions/60330263/ar-js-is-it-possible-to-update-the-location-of-a-gps-entity-place

### Tutorial for location-based AR.js:
- https://medium.com/swlh/build-your-location-based-augmented-reality-web-app-a841956eed2c 
- Repo: https://github.com/nicolocarpignoli/location-based-ar-tutorial/tree/master/static-places 

### Examples with A-Frame and AR.js:
- https://github.com/inspiredlabs/ar.js/
- Click on links for live demo
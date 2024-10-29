## :dart: About

Use augmented reality (AR) to pick and place a selection of furniture models into your surroundings in real-time using your mobile's live video footage of your current surroundings. This project leverages ThreeJS to render the scene and furniture models, WebXR to enable AR mode with estimated real-time environment lighting, hit testing for furniture placement on the floor, and dom-overlay to render the UI.

View the live demo on your mobile at: https://cynthia-3d-webxr-furniture-placement.netlify.app/

https://github.com/cynthiachiu/3D-WebXR-Furniture/assets/20048911/9340db31-3451-47ac-adba-51230ca6abd3

## :checkered_flag: Starting

1. Using your phone, go to the live website at: https://cynthia-3d-webxr-furniture-placement.netlify.app/
2. See the `Enter AR` button at the bottom of the screen and click it
3. Allow phone permissions to use the camera
4. See the row of furniture selections in the bottom banner that is horizontally scrollable. When you click the furniture thumbnail, a white border appears around your selection
5. Pan your phone and walk around and see that a white ring reticle appears to show where you can place your furniture selection
6. In your phone, white the white ring reticle present, tap the phone screen and see your furniture selection appear in place of the reticle
7. You can switch furniture selections and continue walking around and placing furniture
8. See that as you walk around and pan your phone, you are able to walk around the furniture and view it in 3D in real-time
9. Clik `Stop AR` to exit the experience

## :sparkles: Features

:heavy_check_mark: Hit Testing\
:heavy_check_mark: Real-Time Environment Light Estimation\
:heavy_check_mark: Augmented Reality with WebXR\
:heavy_check_mark: Realistic 3D Models with Textures\
:heavy_check_mark: Horizontally Scrollable Furniture Selection\
:heavy_check_mark: Dom-Overlay

## :rocket: Technologies

The following tools were used in this project:

- [ThreeJS](https://threejs.org/)
- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://immersiveweb.dev/)

## :white_check_mark: Requirements

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: Starting

```bash

# Install dependencies
$ npm install

# Run the project
$ npm start

# The server will initialize in the <http://localhost:3000>.

# You can use ngrok to generate a link and try on your mobile with the secure ngrok link.
```

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

Made with :heart: by <a href="https://github.com/cynthiachiu" target="_blank">cynthiachiu</a>

&#xa0;

<a href="#top">Back to top</a>

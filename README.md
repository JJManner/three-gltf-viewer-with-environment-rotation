# glTF Viewer with Environment Rotation and Simplified User Interface 

Preview glTF 2.0 models in WebGL using three.js and a drag-and-drop interface. 

This version has HDRI environment rotation that can illuminate 3D model from the selected direction. It also has a simplified and re-organised user interface for adjusting the environment visibility and lighting, including also some new .exr backgrounds for user to choose. Background visibility can be activated easier, when it is organised right below the Lighting HDRI environment selection. Also a - **_Help_** - section has been added to inform users how to use the mouse controls. 

Original Viewer: [gltf-viewer.donmccurdy.com](https://gltf-viewer.donmccurdy.com/)

## Quickstart

```
npm install
npm run dev
```

![screenshot](/glTF_GUI_example_2.png)

## glTF 2.0 Resources

-   [THREE.GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader)
-   [glTF 2.0 Specification](https://github.com/KhronosGroup/glTF/blob/master/specification/2.0/README.md)
-   [glTF 2.0 Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models/tree/master/2.0/)

## Known Issues

-   [ ] Limited drag-and-drop support in Safari.

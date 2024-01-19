# SMARC Unity HDRP

Welcome to the HDRP (High Definition Render Pipeline) version of SMARC Unity.
This project has all of the dependencies configured and installed in order to showcase the [SMARC Unity Assets package](https://github.com/martkartasev/SMARCUnityAssets) with minimal effort.

The project contains a simple demo scene as well as some assets not found in the Assets package, such as:
* Imported bathymetry
* Replica of SMaRC testing locations
* ???

## Temporary Installation Instructions

This is due to the packages being private! Unity can only resolve private packages with SSH resolution. If Unity cannot fetch the package, you have to do this.

1. Clone this repo and https://github.com/martkartasev/SMARCUnityAssets
2. Open SMARCUnityHDRP/Packages/manifest.json
3. Under manifest.json, edit the following reference

```
    "com.smarc.assets": "git@github.com:martkartasev/SMARCUnityAssets.git",
```

To your respective local directory, for example

```
    "com.smarc.assets": "file:C:/Users/Mart9/Workspace/SMARCUnityAssets",
```
For more info see https://docs.unity3d.com/Manual/upm-localpath.html

This will be fixed in the future.


## New to Unity?

------

If you have not used unity before I suggest trying out a few tutorials from https://learn.unity.com/

To get started, I suggest you familiarize yourself with the editor from: https://learn.unity.com/tutorial/explore-the-unity-editor-1#

### I cannot see anything!

If you want to jump in quickly to see the sim, follow the next few steps.

1. In the Project Window (tab at the bottom) open: Scenes/WaterSimulation.Unity
2. In the central panel, click on Scene. This is the "Editor" window. The "Game" window is simply a camera that has been set up into the scene.
3. In the Hierarchy (panel on the left side), double click on SAM to pan to it.
4. Click the Play button

From here you should be able to move SAM around using the arrow keys and WASD. You might want to drag and drop the Game window (you can split the view), so you can see both the Scene and Game windows in parallel.

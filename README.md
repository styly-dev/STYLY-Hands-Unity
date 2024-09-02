# STYLY Hands Unity package

This package provides utilities for hand tracking. Currently a script to track hand gestures is provided.

# How to use the tracker
In your scene please prepare an object which has `UnityEngine.XR.Hnads.XRHandTrackingEvents` component. Please add `Styly.Hands.GestureTracker` component to the object you want to track.

![GestureTracker](./Screenshots/GestureTacker.png)


## Component setup
1. Set `UnityEngine.XR.Hands.XRHandTrackingEvents` component to `Hand Tracking Events` field.
2. Set your `Hand Pose` or `Hand Shape` asset in `Hand Shapoe Or Pose` field. 
3. Set up `Gesture Performed` and `Gesture Ended` events to receive gesture events (Unity Event).

## How to test in Unity Editor (This is not perfect)
1. Add [XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.0/manual/index.html) package to your project.
2. Add [XR Device Simulator](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.0/manual/xr-device-simulator.html) to your project on package manager.
3. Add and open `Gestures` sample of XR Hands to your project on package manager.
4. Add `XR Device Simulator` prefab which is included in `XR Device Simulator` folder of `XR Interaction Toolkit` sample.
5. Add `GestureTracker` component to the object you like and setup.

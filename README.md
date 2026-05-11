# vr-kunitaka

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

### VR交差点体験 (VR Intersection Experience)

A web-based VR experience showcasing two real-world intersections in Takefu, Fukui, Japan, built from LiDAR scan data using A-Frame.

## Demo

Experience the intersections live in your browser:

👉 **https://code4fukui.github.io/vr-kunitaka/**

The demo features two explorable scenes:
- **Takefu High School Intersection (`cross1.html`):** A static scene allowing you to explore the scanned environment.
- **S-Curve Intersection (`cross2.html`):** A dynamic scene featuring a continuously moving car.

## Features
- **Two Realistic Environments:** 3D models of real intersections captured with LiDAR.
- **Interactive WebXR Experience:** Built with [A-Frame](https://aframe.io/) for in-browser VR and 3D viewing.
- **VR-Ready Controls:** Navigate the scenes using teleportation in a VR headset.
- **Cross-Platform 3D Models:** Assets are provided in both `.glb` (glTF) and `.usdz` formats for use in various 3D and AR applications.

## How to Use

### Viewing the Demo
Open the [demo link](https://code4fukui.github.io/vr-kunitaka/) in a WebXR-compatible browser. You can explore on a desktop using your mouse and keyboard (WASD keys) or enter VR mode with a compatible headset.

### Using the 3D Assets
The 3D models are available in the repository's root directory. You can download and import them into your own projects.
- **Intersections:** `kunitaka-cross1-lidar.glb`, `kunitaka-cross2-lidar.glb`
- **Car:** `car-edit.glb`

## Credits
A project by [Code for FUKUI](https://github.com/code4fukui).

## License
This project is available under the MIT License.
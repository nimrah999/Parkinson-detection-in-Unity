# Parkinson-detection-in-Unity

This project integrates virtual reality (VR) with an ONNX-based machine learning model for real-time Parkinson's detection through spiral drawing analysis.

Project Overview

Goal: Enable early detection of Parkinson's disease by analyzing user-drawn spirals in a VR environment.

Technologies: Unity (with XR toolkit), ONNX for machine learning inference, and VR interaction via XR Rig.

Features

VR environment for user interaction using XR Rig.

Real-time Parkinson's detection with ONNX model.

VR interaction with UI Canvas elements and buttons.

File Structure

Parkinson01.unitypackage: Contains the Unity project package with the VR scene and ONNX model integration.

README.md: Project documentation.

parkinson's spiral model.tm: Trained machine learning model for spiral analysis.

Setup Instructions

Prerequisites:

Unity 2021.3 LTS or later

XR Plugin Management enabled (for VR support)

Import the Package:

Open Unity and go to Assets → Import Package → Custom Package.

Select Parkinson01.unitypackage and import all assets.

Configure XR Setup:

Ensure XR Plugin Management is installed via Project Settings → XR Plugin Management.

Set up the XR Rig prefab in the scene.

Run the Project:

Open the provided VR scene.

Connect your VR headset.

Press Play to interact and start real-time Parkinson's detection.

Usage

Navigate through the VR environment using the XR Rig.

Draw spirals using the virtual interface.

The ONNX model analyzes the spiral in real-time and provides feedback.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

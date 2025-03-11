# Parkinson's Detection in VR

This project integrates virtual reality (VR) with an ONNX-based machine learning model for real-time Parkinson's detection through spiral drawing analysis.

## Project Overview

**Goal:** Enable early detection of Parkinson's disease by analyzing user-drawn spirals in a VR environment.

**Technologies:** Unity (with XR toolkit), ONNX for machine learning inference, and VR interaction via XR Rig.

## Features

- VR environment for user interaction using XR Rig.
- Real-time Parkinson's detection with ONNX model.
- VR interaction with UI Canvas elements and buttons.

## File Structure

- **Parkinson01.unitypackage**: Contains the Unity project package with the VR scene and ONNX model integration.
- **parkinson's spiral model.tm**: Trained machine learning model for spiral analysis.

## Setup Instructions

### Prerequisites:

- Unity 2021.3 LTS or later
- XR Plugin Management enabled (for VR support)

### Import the Package:

1. Open Unity and go to `Assets → Import Package → Custom Package`.
2. Select `Parkinson01.unitypackage` and import all assets.

### Configure XR Setup:

1. Ensure XR Plugin Management is installed via `Project Settings → XR Plugin Management`.
2. Set up the XR Rig prefab in the scene.

### Run the Project:

1. Open the provided VR scene.
2. Connect your VR headset.
3. Press **Play** to interact and start real-time Parkinson's detection.

## Usage

1. Navigate through the VR environment using the XR Rig.
2. Draw spirals using the virtual interface.
3. The ONNX model analyzes the spiral in real-time and provides feedback.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

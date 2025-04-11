# Roomify 3D

Roomify 3D is an augmented reality (AR)-powered interior design application that helps users visualize and arrange furniture in their physical space using real-time mobile AR experiences. Designed to make home design more intuitive and interactive, Roomify 3D bridges the gap between creative vision and practical implementation.

[Project Source Code](https://drive.google.com/file/d/your-file-id/view?usp=sharing) <!-- Replace with your actual Drive link -->


## Features

- **AR-Based Furniture Placement**: Virtually place 3D models of furniture in your actual space using ARKit/ARCore.
- **Real-Time Layout Visualization**: View your home design as you make changes, ensuring a precise and immersive experience.
- **Furniture Scaling & Rotation**: Adjust the size and orientation of furniture models to match your layout perfectly.
- **Clean & Responsive UI**: Developed using Unity and integrated with Firebase for authorization.

## Technologies Used

- **Unity 3D** (2022.3 LTS)
- **AR Foundation** (ARKit & ARCore support)
- **Firebase Auth**
- **Blender**

## Installation & Setup (Development)

To open and run Roomify 3D in Unity:

### 1. Open the Project in Unity

1. Open Unity Hub
2. Click "Open"
3. Navigate to the project folder
4. Select the folder to open the project
5. Ensure you are using Unity version 2022.3 LTS

### 2. Switch Platform

1. In Unity, go to `File > Build Settings`
2. Choose either Android or iOS
3. Click "Switch Platform"

### 3. Set Up AR Foundation and Firebase

- Enable AR features via the AR Foundation package

**For Android:**
1. Add `google-services.json` to `Assets/Plugins/Android`

**For iOS:**
1. Add `GoogleService-Info.plist` to `Assets`
2. Ensure Firebase is properly initialized and authentication is enabled in the Firebase Console

### 4. Build and Run

1. Connect your physical Android or iOS device
2. In Unity, go to `File > Build and Run` to deploy the app to your device

### 5. Clone the Repository

To get the source code:

```bash
git clone https://github.com/ofc-nitin/Roomify3D.git

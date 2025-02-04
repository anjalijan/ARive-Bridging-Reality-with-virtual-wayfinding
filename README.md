# ARive-Bridging-Reality-with-virtual-wayfinding

### ARrive is an Android-based indoor navigation system developed for OTH-AW university using ARCore and Unity.
### The system provides AR-guided navigation within the Digital Campus building, featuring QR code recentering and real-time path visualization. 

### Features:
- Automatic calculation of the optimal route.
- AR-based navigation with real-time path visualization
- QR code position recentering system
- Dynamic minimap that shows user's current location and path
- Room selection and path finding
- Toggle line visibility option
- QR code detection and recentering
 
 ### [Technical Requirements]
- Android device with ARCore support
- Unity 2021.3 or higher
- ARCore SDK
- AR Foundation
- ZXing library for QR code detection
- TextMeshPro (for UI elements)

 ### [How To Set It Up?
 1) Clone the repository
 2) Open project in Unity
 3) Build and deploy to Android device, to deploy: connect Android phone with USB to your system and in android turn on the developer mode by tapping 7 times on build number from andriod and turn on USB Debugging option
 4) Open the app and select the destination then follow the path

### [How It Works?]
1) When the user launches the app, they can select the destination from the start point
2) User(blue indicator) need to follow the navigation path(red line) to reach the selected destination(yellow cube)
3) The user can recenter their position by scanning the QR code placed at Elevator, which will reset their location to the elevator. After recentering, they can select their destination.
 


 ### [API Documentation]
#### Core Classes
##### Target
    - Manages target location data and position references
    - Handles serialization of navigation targets
##### SetNavigationTarget
    - Controls path generation and visualization
    - Manages destination selection and path rendering
    - Handles line visibility toggling
    - Real-time path calculation using NavMesh
##### QRCodeRecenter
    - Processes camera frames for QR code detection
    - Manages position recalibration
    - Handles AR session management
    - Controls position and rotation updates
 
####  System Components
##### Navigation Interface
    - Room selection and destination setting
    - Path visualization controls
    - Minimap toggle functionality
    - Real-time position tracking
##### QR Code Interface
    - Camera frame processing
    - Position recalibration
    - Location updates
    - Session management
##### Integration Points
    - ARCore integration for AR features
    - Unity NavMesh for pathfinding
    - Camera management for QR scanning
    - Position tracking system
##### User Interaction Methods
    - Destination selection via dropdown
    - Path visibility toggle
    - QR code scanning
    - Position updates

#### adding the google drive link as the unity file is large and github has storage limitations
- https://drive.google.com/file/d/1lF5JAHpgh-yLx6ECWi_SCNoFK7VtMJSm/view?usp=sharing

<hr>

# README - SpectraGuard-Swift

## Table of Contents

1. Introduction
2. Installation
3. How to Use
4. Extensions
5. Troubleshooting
6. Versions
7. Contributing

<hr>

### 1. Introduction
- this project aimed to create a digital twin of a room, and place own (or recorded) 3D models inside this room, also adding a floating label
- for now, this code uses the Lidar sensor of an iPhone and creates point clouds of a room, but it is not storable and 3D models can't be added

<hr>

### 2. Installation
- open your terminal and clone this Repository via this command:
```shell
git clone https://github.com/SpectraGuard/SpectraGuard-Swift
```
- now you can open Xcode and to execute the App, following this steps:
	- navigate to the project folder and open the `SceneDepthPointCloud.xcodeproj` in the Xcode IDE
	- open the main project file: ![[project_folder.png]]
	- navigate to `Targets` -> `SceneDepthPointCloud` -> `Signing & Capabilities` -> and change the Team to your Developer-Account
	- plug your Developer phone in and run the Application on your device

<hr>

### 3. How to Use
- start the application on your iPhone
- you get prompted with the message, asking for camera access -> click `Yes`
- the camera starts recording the point clouds automatically and you can scan now your room

<hr>

### 4. Extensions
- possible further extensions:
	- adding the functionality to save the recorded point cloud
	- a new graphical user interface, where the user can see all his previous recordings
	- deleting records
	- add labels to real objects in the saved recording
	- add other 3D objects in the saved recording

<hr>

### 5. Troubleshooting
#### 5.1 List of all supported iPhone Devices
- iPhone 12 Pro
- iPhone 12 Pro Max
- iPhone 13 Pro
- iPhone 13 Pro Max
- iPhone 14 Pro
- iPhone 14 Pro Max
- iPhone 15 Pro
- iPhone 15 Pro Max
- all iPad Pro (2020 Version or later)
- supported devices for Apple's ARKit: [Supported iOS devices](https://www.arcade-xr.com/is-my-device-ar-compatible)

#### 5.2 Activating iPhone Developer Mode
>to activate the Developer Mode, be sure that you know what that means
- it is recommended, that you don't activate this mode on your personal iPhone Device
- read the `Developer Mode Apple Documentation`
- create, if needed, a Backup from your Device
- understand the risks
	- e.g.: common problems including
		- data loss
		- stability problems
		- security risks
		- loss of warranty
		- incompatability with software updates

- activate the Developer Mode
	- Settings > Privacy & Security > scroll down to the bottom > Developer Mode > toggle the button
	- Einstellungen > Datenschutz & Sicherheit > navigiere ganz nach unten > Entwicklermodus > aktiviere den Modus

#### 5.3 Managing Apple Bundle Identifier
- if you want to run the Application on your iOS iPhone, ensure that the iPhone is in `Developer Mode`
- navigate to the main folder and open the `.xcodeproj`
- now press on the left hand side, the blue main icon
- navigate on `TARGETS`
- change the `Bundle Identifier` to a unique String, for example: `com.App_AR.SpectraGuard`
- click on `Team` and chose your Account
- check the box `Automatically manage signing`
- now you can (with your iPhone plugged to your MacBook) run the App with `CMD + R` or the Run-Button

#### 5.4 Untrusted Developer Error Message
- 

#### 5.5 Helpful Links
- [iPhone Entwicklermodus](https://www.aiseesoft.de/resource/iphone-entwicklermodus.html)
- [Developer Mode Apple Documentation](https://developer.apple.com/documentation/xcode/enabling-developer-mode-on-a-device)
- [Apple - Point Cloud Using Scene Depth](https://developer.apple.com/documentation/arkit/arkit_in_ios/environmental_analysis/displaying_a_point_cloud_using_scene_depth)
- [ARKit4 - WWDC 2020](https://developer.apple.com/videos/play/wwdc2020/10611/)
- [GitHub arkit-scenedepth-pointcloud](https://github.com/isakdiaz/arkit-scenedepth-pointcloud)
-  [Bundle ID](https://developer.apple.com/documentation/appstoreconnectapi/bundle_ids)
- [Register an App ID](https://developer.apple.com/help/account/manage-identifiers/register-an-app-id/)


<hr>

### 6. Versions
- `1.0.0` - Basic function, point cloud generating

<hr>

### 7. Contributing
- [GitHub - Nahedg](https://github.com/Nahedg)
- [GitHub - Beri336](https://github.com/beri336)
- [GitHub - Xeniawdrz](https://github.com/xeniawdrz)

<hr>
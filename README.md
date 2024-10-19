# hello-aaos

Hello World simple app for Android Automotive OS (**AAOS**) app using Android Studio. Includes how to create an emulator and run the app on it.

<img height="300" src="./docs/00-device-closeup.png">

## Relevant files

- [`AndroidManifest.xml`](./automotive/src/main/AndroidManifest.xml) - Automotive OS specific manifest entries
- [`automotive_app_desc.xml`](./automotive/src/main/res/xml/automotive_app_desc.xml) - Automotive OS specific app description
- [`MainActivity.java`](./automotive/src/main/java/com/zachgrimaldi/helloaaos/MainActivity.java) - Main activity
- [`activity_main.xml`](./automotive/src/main/res/layout/activity_main.xml) - Main activity layout

## Prerequisites

- Android Studio (this was developed with `android-studio-2024.2.1.10-mac`)

## Steps

1. Clone this repository. `git clone https://github.com/zpg6/hello-aaos`

2. Open the project in Android Studio.

3. Create an Android Automotive OS emulator

4. Run the app on the emulator

## Create an Android Automotive OS emulator

### Create a virtual device
<img height="300" src="./docs/01-create-virtual-device.png">

### Select the hardware profile
<img height="500" src="./docs/02-automotive-display.png">

### Configure the system image
<img height="500" src="./docs/03-system-image.png">

### Complete the device setup
<img height="500" src="./docs/04-complete-device-setup.png">

### Device created
<img height="300" src="./docs/05-device-created.png">

### First boot
<img height="800" src="./docs/06-device-first-boot.png">

## Run the app on the emulator

<img height="600" src="./docs/07-app-running.png">

# Lockscreen Bypass
This is a lockscreen that does not lock the screen.

## Why you did that?
I had a problem to use old Android devices that the touch screen isn't working.
So the idea came from this necessity. I was looking for a way to unlock those devices.

## How to install
Donwload this project with **git**, or get the **zip** file.
Open your terminal in the project dir, and type:
```
./gradlew installDebug
```

### Why install on debug?
There's no need to create a release key nor apk, may in the future, I don't know.
This is because this app is not intended to be a *release app*, but I can do it if you need, create a issue and I'll release that.

### What's needed to install?
As I said before, this is not intended to be a release app, but if you want to test this in your device **ask for it** and I'll make a release APK, so you won't need to install it all.
* Java SDK
* Android SDK
* Device in development mode

## How can I help
Create a Issue, make a pull request everything is welcome.
This is working on my **Motorola Droid 1** (api 10 with cyanogenMod), so my target was reached.
It may not work on newer devices, if you have a new device and it's not working create a issue.

## Thanks
Thanks to tue user @Joisar, this project is basically a fork of his [Lockscreen sample](https://github.com/Joisar/LockScreenApp), if you're interested take a look.

Thanks to @xSAVIKx, he made an app that allow us to control the android without the screen.
Take a look, [here](https://github.com/xSAVIKx/AndroidScreencast), you just need to download a jar file.
I made a fork, it's under-construction, to replace the way to send commands to the device, because it's not working on my old phone.
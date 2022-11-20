# mi-watchface-uploader
A mod for uploading custom watchfaces to xiaomi wearable devices

# How to install
Android 6.0+ required

### Non root
- Download and install `mi-fitness-miwuploader.apk` (make sure to uninstall mi fitness first)

### Root
- Download [LSPosed Framework](https://github.com/LSPosed/LSPosed)
- Download and install `miwuploader.apk` 
- Enable Mi Watch Face Uploader in LSPosed Manager


**Download links are in the [releases](https://github.com/Mino260806/mi-watchface-uploader/releases/) section**

# How to use
Once you have a watch face file ready to be installed:
1. Copy the watch face to `Android/data/$PACKAGE_NAME/files/WatchFace` (`$PACKAGE_NAME` might be `com.mi.health` or `com.xiaomi.wearable` depending on your version of mi fitness)
2. Open Mi Fitness and jump to watch faces gallery, choose any online watchface and apply it (make sure that the watchface isn't installed on the watch, if so, delete it first)
3. That's it!

# Notes
- To delete a custom watch face from the watch, you have to delete the watch face which you linked to it (see step 2 from "How to use")
- This mod has been tested with Redmi Watch 2 Lite, but it might work with other watches as well (feel free to test it out)

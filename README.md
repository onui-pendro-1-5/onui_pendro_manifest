# OnUI-Pendro-2.0 #

OnUi-pendro-2.0 is based on lineageOS , Pixel Experience & Aosp. Our aim is to push Samsung experience stuff and as well as some Oxygen os stuff in to all the Smart phones . So we really thank to all the  Owners of Aosp , lineageOS & Pixel Experience for such a beautiful and standard code.


### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/onui-pendro-1-5/onui_pendro_manifest.git -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch onui_$device-userdebug

# Build the code
$ make -jx  bacon
```

Credits
-------

* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**PixelExperience**](https://github.com/PixelExperience)





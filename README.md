# HOW-TO Build

1) Initialize the repository

- repo init -u git://github.com/LineageOS/android.git -b lineage-15.0

2) Add my manifest to the .repo folder (don't worry about the alert you will get about being DEPRECATED)

3) Sync latest LineageOS 14.1 sources

- repo sync

4) You are good to go, proceed with the compiling process

- export WITH_TWRP=true

5) FOR GT-I9500 (ja3gxx) only. OTHERWISE, REPLACE THE CODENAME WITH OTHERS SUPPORTED (check the manifest).

- . build/envsetup && lunch lineage_ja3gxx-userdebug
- brunch lineage_ja3gxx-userdebug
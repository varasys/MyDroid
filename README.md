# MyDroid
Free and Open Source Software (FOSS) Android fork with proper permission model, native backup support and MyCloud integration

MyDroid is a fork of Android intended to correct the following deficiencies:
1. Root access by default (with sudo protection)
2. Identity based external interactions
3. Proper permissions model:
    * Not only "set and forget"
    * Instance based permission approvals (with option for "set and forget")
4. Clear seperation between the following to facilitate better disaster recovery and transfer between devices:
    * Application Manifests (to facilitate clean re-installation of software)
    * Application Data (to facilitate data backups)
5. Ephemeral items (including the OS itself) stored on device ROM - and ALL data stored on external SD card
6. Integration with MyCloud (FOSS personal cloud intended to be installed on the user's VPS)
7. Simplified architecture (focused on benefiting the end users and not app developers or any single corporate entity)

MyDroid is meant to run apps developed for Android, but will be focused on drawing attention and promoting the F-Droid FOSS app repository.



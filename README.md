# MyDroid
Free and Open Source Software ([FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software)) Android fork with proper permission model, native backup support and [MyCloud](https://github.com/varasys/MyCloud) integration using secure [ITPS](https://github.com/varasys/ITPS) networking protocol.

MyDroid is meant to bring the mobile experience back closer to the desktop experience by providing a mobile OS that will work for most people out of the box, but also allows the same flexability as Linux on a desktop for people who want that.

MyDroid is a fork of Android intended to correct the following deficiencies:
1. No artificial contraints added for commercial reasons or by carriers
2. Root access by default (with sudo protection)
3. Identity based external interactions
4. Proper permissions model:
    * Not only "set and forget"
    * Instance based permission approvals with option for "set and forget" (so if an app needs location services it will ask each time, and then be locked out again after the app is closed)
5. Clear seperation between the following to facilitate better disaster recovery and transfer between devices:
    * Application Manifests (to facilitate clean re-installation of software)
    * Application Data (to facilitate data backups)
6. Ephemeral items (including the OS itself) stored on device memory - and ALL data stored on external SD card (so SD card is mandatory! - but this also allows for a form of identity switching by switching SD cards (or partitions on the same SD card))
7. Integration with [MyCloud](https://github.com/varasys/MyCloud) (FOSS personal cloud intended to be installed on the user's VPS)
8. Simplified architecture (focused on benefiting the end users and not app developers or any single corporate entity)

MyDroid is meant to run apps developed for Android, but will be focused on drawing attention and promoting the [F-Droid](https://f-droid.org/) FOSS app repository.

Additional features:
1. Complete and total process isolation with sandboxed data storage (you can try something and then be assured of being able to completely wipe it and ALL traces, including data)
2. Interface between apps uses a more secure model (for instance, instead of allowing access to the contact list, a program will use an API to launch the contacts app and then accept whatever is returned - therefore the program will not actually have any access to the contact list, just the contact(s) the user selected)

## Team Skills Needed
1. Android Developers

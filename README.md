# MIUI Sources for Nexus 6P (angler)

It's an unfinished project yet, please wait for downloads

If you want to build miui yourself using this repository, setup your linux for android build marshmallow with JDK7 and follow these commands:


- mkdir /build/MIUI
- cd /build/MIUI
- repo init -u git://github.com/airwa1kin7/patchrom.git -b marshmallow
- repo sync
- . build/envsetup.sh && cd angler && make fullota
- adb sideload out/fullota.zip


If you use this to build and want to publish your work, please give me the credits for the base.

I will not base it on any angler projects already published, just use some commits to make my work easier.

If you know any way to solve bugs, please make an pull request and receive the credits.

If you have any problems with ROM build, I'm not here to help you, everything that is on github was tested before.

forked from libnijunior/patchrom_angler

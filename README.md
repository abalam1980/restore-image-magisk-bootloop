# restore-image-magisk-bootloop

fastboot devices
fastboot boot restore.img
let it boot in system
adb devices


adb wait-for-device shell magisk --remove-modules

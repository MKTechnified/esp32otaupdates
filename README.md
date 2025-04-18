# esp32otaupdates

Step 1: Update Firmware file in github
update code as your needs -> update String currentVersion = "1.5" to "1.6"(latest version) in sketch file in arduino ide -> export compiled bin file -> locate your sketchname.ino.bin file  and rename it to firmware.bin copy the firmware.bin -> github -> add files -> upload file -> upload firmware.bin -> commit changes.

Step 2: Update version in github
change version number in version.txt file as per the firmware.bin file

# KillDroid

A bash script designed to monitor for android emulators being started and killing the process after a specified amount of time.

### Requirements

The folder containing adb must be added to the path variable (i.e. typing adb devices into the command line exactly like that should run)

A bash shell.

### Caveats

Has only been tested on a mac.

### How to Run

There are two ways to run killdroid
./killdroid <x:integer> - monitors for emulators for x minutes and kills the emulator after 20 minutes (example: ./killdroid 30 will monitor for 30 minutes)

./killdroid <x:integer> <y:integer> - monitors for emulators for x minutes and kills the emulator after y minutes (example: ./killdroid 30 15 will monitor for 30 minutes and kill the emulator after 15 minutes)


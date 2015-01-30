This hook creates an automatically generated version number which will be incorporated in the firmware.

To install the hook, place the hook scripts in the hooks folder of the project's .git repository.

Then create a remote repository on github and call that repository "github".
If you are going to share your .hex file with anyone, be sure to push the corresponding source
to the github repository.

Note: At the present time, the Arduino IDE does not provide a mechanism to rebuild the _Version.h file
before each build. Therefore, you must do a git checkout of your source immediately before building
in order to have the build version information updated. An effort is underway to create the mechanism
to permit this to be done automatically.
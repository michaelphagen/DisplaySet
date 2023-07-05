# DisplaySet
App Builder for "Set Separate Displays" and "Set Mirrored Displays" apps

This script creates 2 application bundles that will set a the computer's display to pre-determined settings for mirrored and separate displays. This is useful if the native resolution of one of your displays is unusable for some reason (using an active HDMI extender, etc.)

## Configuration
These pre-determined settings are specified in the Displays.csv file as semicolon separated values:

```
id;resolution@refreshRate;positionx,positiony
```
These values can be obtained using [displayplacer](https://github.com/jakehilborn/displayplacer) which is included in this repository. Running displayplacer will output the current display settings at the bottom of it's output. These values can be copied and pasted into the Displays.csv file.

## Usage
1. Clone this repository
2. Input the desired display settings into the Displays.csv file
3. Run the build script
4. The application bundles will be created in the root of the repo

## Thanks
Thanks to [Jake Hilborn](https://github.com/jakehilborn) for creating [displayplacer](https://github.com/jakehilborn/displayplacer) and [Dean Scarff](https://github.com/p00ya) for creating [displaymode](https://github.com/p00ya/displaymode)
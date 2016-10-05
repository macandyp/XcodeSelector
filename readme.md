# XcodeSelector

## Problem

Sometimes you want to have multiple versions of Xcode installed on your machine. Sure, you think it'll never happen to you, but then it does. Using `xcode-select` in Terminal isn't difficult, but it does get tedious having to go in all the time to check. 

## Solution

XcodeSelector is simply a Service that is globally availble that checks for any version of Xcode in your Applications directory, and asks which one you want to work with. It does ask for your system password, but only because `xcode-select` requires root execution. **This workflow does nothing with your password, otherwise**. 

## Using
    1. From any application, open the Services menu, and select XcodeSelector.    
<img src="https://github.com/macandyp/XcodeSelector/blob/master/screenshot2.png" width="300"/>

    2. Pick the version of Xcode you'd like to work with. 
<img src="https://github.com/macandyp/XcodeSelector/blob/master/screenshot.png" width="300"/>

### Contributors
  * Andy Pereira: [Twitter](https://twitter.com/macandyp)
  * James Headrick: [Twitter](https://twitter.com/jwheadricknj)

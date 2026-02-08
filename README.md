[![](https://jitpack.io/v/functionland/fula-build-aar.svg)](https://jitpack.io/#functionland/fula-build-aar)

# fula-build-aar
Android Wrapper for fula mobile

This repository contains the .aar file for the Android wrapper of go-fula for react native (react-native-fula) and updates the jitpack.io library repo

Created with gomobile with Android NDK 25: 
gomobile bind -v -o mobile.aar -target=android -androidapi 26 github.com/functionl
and/go-fula/mobile 

or cd go-fula and 

```
gomobile bind -v -o mobile.aar -target=android -ldflags="-checklinkname=0" -androidapi 26 ./mobile
```


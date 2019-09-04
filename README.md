# open-android-emulator
Opens the android emulator and connects to the latest version device. (Use it with React Native and IntelliJ)


### Open virtual device with the latest version API.
```
$ ./open_android_emulator
```

### Open target virtual device
```
$ ./open_android_emulator Pixel_3_XL_API_28
```

### Example of usage in IntelliJ
[![Example of usage in IntelliJ](http://img.youtube.com/vi/PJO1Um3gCTU/0.jpg)](https://youtu.be/PJO1Um3gCTU)

- Go to Run/Debug Configurations.
- Add `React Native`.
- Find `Before Launch`.
- Click `+` to add new configuration.
- Add `Run External Tool` and Click `+` again.
- In Tool Settings - Program - Browse, browse `open_android_emulator`.
- Click OK.
- Run.

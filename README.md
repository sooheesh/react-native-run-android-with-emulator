# react-native-run-android-with-emulator
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

![](https://user-images.githubusercontent.com/24663059/64314601-860ff380-cfea-11e9-8f8d-ddffa3fd8f30.png)

- Find `Before Launch`.
- Click `+` to add new configuration.
- Add `Run External Tool` and Click `+` again.

![](https://user-images.githubusercontent.com/24663059/64314606-8ad4a780-cfea-11e9-802f-ebf38e4160fa.png)

- In Tool Settings - Program - Browse, browse `open_android_emulator`.

![](https://user-images.githubusercontent.com/24663059/64314608-9031f200-cfea-11e9-8ce9-415026d78284.png)

- Click OK.
- Run.



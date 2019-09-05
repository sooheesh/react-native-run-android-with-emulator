# react-native-run-android-with-emulator
Opens the android emulator and connects to the latest version device. (Available with React Native and/or IntelliJ)

### Example command line usage with React Native
```
$ ./open_android_emulator && react-native run-android
```

---

### Open virtual device with the latest version API.
```
$ ./open_android_emulator
```

![](https://user-images.githubusercontent.com/24663059/64327445-a9489c00-d006-11e9-92ff-cdb341706ad5.png)


### Open target virtual device
```
$ ./open_android_emulator Pixel_3_XL_API_28
```

---

### Example usage in IntelliJ
[![Example of usage in IntelliJ](http://img.youtube.com/vi/PJO1Um3gCTU/0.jpg)](https://youtu.be/PJO1Um3gCTU)


### Installation guide
- Go to Run/Debug Configurations.
- Add `React Native`.

![](https://user-images.githubusercontent.com/24663059/64314837-501f3f00-cfeb-11e9-9094-ce8d39c683c7.png)
![](https://user-images.githubusercontent.com/24663059/64314838-501f3f00-cfeb-11e9-92bf-014e241f08df.png)

- Find `Before Launch`.
- Click `+` to add new configuration.
- Add `Run External Tool` and Click `+` again.

![](https://user-images.githubusercontent.com/24663059/64314839-50b7d580-cfeb-11e9-9eb4-68f5b7896fc3.png)
![](https://user-images.githubusercontent.com/24663059/64314840-50b7d580-cfeb-11e9-9152-b92f60f29d2d.png)

- In Tool Settings - Program - Browse, browse `open_android_emulator`.

![](https://user-images.githubusercontent.com/24663059/64314841-50b7d580-cfeb-11e9-9ae5-d095b07cc42f.png)

- Click OK.
- Run.

---

### Permission issue

Modify permission to give IntelliJ access to this file.

```
$ chmod a+x open_android_emulator
```











# RoundImageView
Rounded image view for android specially used for profile photos.

[![](https://jitpack.io/v/com.queensherainfotech/RoundImageView.svg)](https://jitpack.io/#com.queensherainfotech/RoundImageView)

Project level gradle
------
```
allprojects {
    repositories {
        google()
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```


App level gradle
------
```
dependencies {
    ...
    implementation 'com.queensherainfotech:RoundImageView:1.0.0'
}
```

Usage
-----
```xml
<com.queensherainfotech.roundimagelibrary.RoundImageView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_centerInParent="true"
    android:src="@mipmap/profilephoto"/>
```

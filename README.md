# ![Logo] (https://github.com/arunk1504/android-utils/blob/master/sample/Android8/res/drawable-mdpi/ic_launcher.png) Android Commons

Android Commons aims to provide quick, easy and ready to use set of functionalities and utilites. It consist of various method for Bitmap Image Scaling, Application, Network, I/O , SQLite database and many others.

## Features
 * Wide customization utilities for scaling and recycling Bitmap.
 * `ExtendedSQLiteOpenHelper` extension of `SQLiteOpenHelper` with enhance features for database operations.
 * Extensive File and Directory reading, writing and fast information retrieval methods.
 * Tons of Nuts and Bolts for String, Maths and other various features.
 * Android 2.2+ / API Level 8+ Support.
 
## Usage

#### 1. Include library

**Manual:**
 * [Download JAR](https://github.com/arunk1504/android-utils/blob/master/downloads/utils-android-1.0.0.jar)
 * Put the JAR in the **libs** subfolder of your Android project

![jar library in libs](https://github.com/arunk1504/android-utils/blob/master/wiki/dir_structure.png)


 * Make sure the library is included in the *Build Path* for project.

![build path](https://github.com/arunk1504/android-utils/blob/master/wiki/build_path.png)


#### 2. Android Manifest
``` xml
<manifest>
	<!-- Include following permission if you load images from Internet -->
	<uses-permission android:name="android.permission.INTERNET" />
	<!-- Include following permission if you want to cache images on SD card -->
	<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <!-- Include when checking the network state -->
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
	...
</manifest>
```

#### 3. Application or Activity class
``` java
public class MyActivity extends Activity {
        EditText edtText;
	public void randomMethod() {
             EditTextUtils.clearEditText(edtText);
	}
}
```

![usage](https://github.com/arunk1504/android-utils/blob/master/wiki/usage.png)
 * Look [here](https://github.com/arunk1504/android-utils/wiki/Useful-Info) if you any have issues while deploying the app using proguard.

## Package Structure / UML Diagrams

* **[App Package](https://github.com/arunk1504/android-utils/wiki/UML-and-Package-Structure#app-package)**
* **[DB Package](https://github.com/arunk1504/android-utils/wiki/UML-and-Package-Structure#db-package)**
* **[Image Package](https://github.com/arunk1504/android-utils/wiki/UML-and-Package-Structure#image-package)**
* **[Java Package](https://github.com/arunk1504/android-utils/wiki/UML-and-Package-Structure#java-package)**
* **[Net Package](https://github.com/arunk1504/android-utils/wiki/UML-and-Package-Structure#net-package)** 
* **[View Package](https://github.com/arunk1504/android-utils/wiki/UML-and-Package-Structure#view-package)**


## Downloads
 * **[utils-android-1.0.0.jar](https://github.com/arunk1504/android-utils/blob/master/downloads/utils-android-1.0.0.jar)**
 * **[utils-android-1.0.0-with-sources.jar](https://github.com/nostra13/Android-Universal-Image-Loader/raw/master/downloads/universal-image-loader-1.9.3-with-sources.jar)** (for Eclipse)
 * **[Sample App on Github](https://github.com/arunk1504/android-utils/blob/master/downloads/Android8-1.0.0.apk)**

 
## License

    Copyright 2017 Arun Nair

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

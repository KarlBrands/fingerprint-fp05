# fingerprint-fp05
A nifty (Android) library for verification and authentication of fingerprint on the fgtit-fp05 mobile device
Official release library for fgtit-fp05 device.

Usage:

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

```gradle

    allprojects {
    		repositories {
    			...
    			maven { url 'https://jitpack.io' }
    		}
    	}

 ```

Step 2. Add the dependency
```gradle
    dependencies {
    	        compile 'com.github.interwap:fingerprint-fp05:v1.6'
    	}
 ```

Get more information about versions and releases here: [`jitpack`](https://jitpack.io/#interwap/fingerprint-fp05/v1.6)


Update: Version 1.6 (Stable)
- Modified Fingerprint Matching algorithm


Update: Version 1.5 (Deprecated)


Update: Version 1.4 (Stable)
- Set value for text size
- Set value for dialog width
- Set value for dialog height
- Check isShowing Status



Update: Version 1.3 (Deprecated)
- Fixed TextSize Bug


License
=======

    Copyright 2017 Ikomi Moses

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
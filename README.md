# my-cool-lib
A cool lib created for a cool medium post about creating cool libraries and this is it's very obvious README file.

The Post:

The Status of the lib: 
[![Release](https://jitpack.io/v/zurche/my-cool-lib.svg)](https://jitpack.io/#zurche/my-cool-lib/v0.1)

How to use this lib in your project:
```groovy
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

Add to your app module build.gradle
```groovy
dependencies {
        compile 'com.github.zurche:my-cool-lib:v0.1'
}
```

What you can do with this lib:
```javascript
Point buenosAiresObeliscoPoint = new Point((float) -34.6037389, (float) -58.3815704);
        
Point nycStatueOfLibertyPoint = new Point((float) 40.6892494, (float) -74.0445004);

float distanceBetweenPoints = LatLonDistanceCalculator.calculateDistance(
    buenosAiresObeliscoPoint, 
    nycStatueOfLibertyPoint);
```

License
--------

    Copyright 2016 Alejandro Zürcher

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

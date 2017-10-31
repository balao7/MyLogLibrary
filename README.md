# MyLog - Library
Simple android logger (2017)

[ ![Download](https://api.bintray.com/packages/pulimet/utils/mylog/images/download.svg) ](https://bintray.com/pulimet/utils/mylog/_latestVersion)      
<a href="http://www.methodscount.com/?lib=net.alexandroid.utils%3Amylog%3A1.1">
<img src="https://img.shields.io/badge/Methods and size-0 | 0 KB-e91e63.svg"/></a> [![License](https://img.shields.io/badge/license-Apache%202-green.svg)](https://www.apache.org/licenses/LICENSE-2.0)


Simple android logger

# Installation

- Add the dependency from jCenter to your app's (not project) build.gradle file:

```sh
repositories {
    jcenter()
}

dependencies {
    compile 'net.alexandroid.utils:mylog:1.1'
}
```


- Add init line in your application class as shown below:

```sh
public class MyApplication extends Application {
    @Override
    public void onCreate() {
        super.onCreate();
        
        MyLog.init(this);
        MyLog.showLogs(BuildConfig.DEBUG);
    }
}
```

* Also don't forget to add: android:name=".MyApplication" at your application tag in AndroidManifest.xml
```sh
 <application
        android:name=".MyApplication"
        ...>
```

# How to use it


 <br>  <br>  <br> 
# License

```
Copyright 2016 Alexey Korolev

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
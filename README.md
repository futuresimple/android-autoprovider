AutoProvider
============
Utility for creating ContentProviders without boilerplate and with heavy customization options.

Features
========

Usage
=====
Build the library and install it in local Maven repository:
```
./gradlew clean installArchives
```

Note: right now you'll need [autoindexer](https://github.com/futuresimple/android-autoindexer) and [forger](https://github.com/futuresimple/forger) available in your local Maven repo as well.

Then add the dependency to your `build.gradle`:

```groovy
repositories {
  mavenLocal()
}

dependencies {
    compile 'com.getbase.android.autoprovider:library:0.1.0'
}
```

Caveats
=======

Credits
=======

License
=======

    Copyright (C) 2015 Jerzy Chalupski

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

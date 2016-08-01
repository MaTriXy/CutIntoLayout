CutIntoLayout
=============

CutIntoLayout allows you to create clear effect on your background.

[![DevLight](https://lh4.googleusercontent.com/-9btnRFp_eVo/V5cfwZsBpMI/AAAAAAAAC4E/s4NGoezKhpAVdVofAoez1QWpzK5Na8_cQCL0B/w147-h20-no/devlight-badge.png)](http://devlight.com.ua)

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-CutIntoLayout-yellow.svg?style=flat)](http://android-arsenal.com/details/1/3316)
[![Android](https://img.shields.io/badge/platform-android-brightgreen.svg?style=flat&label=Platform)](https://github.com/DevLight-Mobile-Agency)
[![Download](https://api.bintray.com/packages/gigamole/maven/cutintolayout/images/download.svg)](https://bintray.com/gigamole/maven/cutintolayout/_latestVersion)
[![Crates.io](https://img.shields.io/crates/l/rustc-serialize.svg?maxAge=2592000&label=License)](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/blob/master/LICENSE.txt)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f1ae9a85f2a84755b567b5e05d7ccf08)](https://www.codacy.com/app/gigamole53/CutIntoLayout?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/CutIntoLayout&amp;utm_campaign=Badge_Grade)

![](https://lh3.googleusercontent.com/fWz9orE3M8vaAuzkxHi0F2m23iuHUYlXmG-lgonEFCU=w210-h282-no)

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/tree/master/app).

Download
------------

You can download a `.jar` from GitHub's [releases page](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/releases).

Or use Gradle jCenter:
```groovy
dependencies {
    repositories {
        mavenCentral()
        maven {
            url  'http://dl.bintray.com/gigamole/maven/'
        }
    }
    compile 'com.github.gigamole.cutintolayout:library:+'
}
```

Or Gradle Maven Central:

```groovy
compile 'com.github.gigamole.cutintolayout:library:1.0.1'
```

Or Maven:

```xml
<dependency>
    <groupId>com.github.gigamole.cutintolayout</groupId>
    <artifactId>library</artifactId>
    <version>1.0.1</version>
    <type>aar</type>
</dependency>
```

Android SDK Version
===================

`CutIntoLayout` requires a minimum SDK version of 11.

Sample
======

`CutIntoLayout` must have child. Only one child.
You can put any view into layout.

`XML` init:

```xml
<com.gigamole.cutintolayout.lib.CutIntoLayout
    android:id="@+id/cut_into_layout"
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_gravity="center"
    android:background="@drawable/sample_bg">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:gravity="center"
        android:text="@string/sample_title"
        android:textColor="@color/white" />

</com.gigamole.cutintolayout.lib.CutIntoLayout>
```

Getting Help
======

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/issues/new).

License
======
Apache 2.0 and MIT. See [LICENSE](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/blob/master/LICENSE.txt) file for details.

Author
=======

Made in [DevLight Mobile Agency](https://github.com/DevLight-Mobile-Agency)

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)

## Support on Beerpay
Hey dude! Help me out for a couple of :beers:!

[![Beerpay](https://beerpay.io/DevLight-Mobile-Agency/CutIntoLayout/badge.svg?style=beer-square)](https://beerpay.io/DevLight-Mobile-Agency/CutIntoLayout)  [![Beerpay](https://beerpay.io/DevLight-Mobile-Agency/CutIntoLayout/make-wish.svg?style=flat-square)](https://beerpay.io/DevLight-Mobile-Agency/CutIntoLayout?focus=wish)
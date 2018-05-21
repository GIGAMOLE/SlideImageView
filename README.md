SlideImageView
==============

Simple and convenient library that allows you to slide images through a view.

[![Android](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wSccEZaclNGN0R5OWc)](https://github.com/DevLight-Mobile-Agency)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Download](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScRWtyVkJ6bEJkS2c)](https://bintray.com/gigamole/maven/slideimageview/_latestVersion)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![License](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScU0tmeFpGMHVWNWs)](https://github.com/DevLight-Mobile-Agency/SlideImageView/blob/master/LICENSE.txt)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Codacy](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScSHhmckZyeGJDcXc)](https://www.codacy.com/app/gigamole53/SlideImageView?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/SlideImageView&amp;utm_campaign=Badge_Grade)

<p align="center">
    <img src="https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScWHZHNTFfMkdCbjA"/>
</p>

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/SlideImageView/tree/master/app).

Warn
====
```
This library is not more supported. 
If you want to add new feature or fix a bug, grab source code and do it. 
If you think your fix or feature would be useful to other developers, 
I can add link of your repository to this README file. 
Thank you for using our libraries.
```

Download
========

You can download a `.aar` from GitHub's [releases page](https://github.com/DevLight-Mobile-Agency/SlideImageView/releases).

Or use Gradle jCenter:
```groovy
dependencies {
    repositories {
        mavenCentral()
        maven {
            url  'http://dl.bintray.com/gigamole/maven/'
        }
    }
    compile 'com.github.gigamole.slideimageview:library:+'
}
```

Or Gradle Maven Central:

```groovy
compile 'com.github.gigamole.slideimageview:library:1.1.4'
```

Or Maven:

```groovy
<dependency>
    <groupId>com.github.gigamole.slideimageview</groupId>
    <artifactId>library</artifactId>
    <version>1.1.4</version>
    <type>aar</type>
</dependency>
```

Android SDK Version
===================

`SlideImageView` requires a minimum sdk version of 8.

Sample
======

<b>Parameters</b>

You can set such parameters as:  
 - source
 - axis (`HORIZONTAL` | `VERTICAL`)
 - rate

<b>Init</b>

Check out in code init:

```java
final SlideImageView slideImageView = (SlideImageView) findViewById(R.id.img_horizontal_slide);
slideImageView.setSource(R.drawable.wide_background);
slideImageView.setRate(0.3f);
slideImageView.setAxis(SlideImageView.Axis.HORIZONTAL);
```

And XML init:

```xml
<devlight.io.library.SlideImageView
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:siv_source="@drawable/long_background"
    app:siv_axis="vertical"
    app:siv_rate="2.0"/>
```

Getting Help
============

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/SlideImageView/issues/new).

Author
======

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)

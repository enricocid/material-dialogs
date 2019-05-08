# Material Dialogs

#### [View Releases and Changelogs](https://github.com/afollestad/material-dialogs/releases)

[![Build Status](https://travis-ci.org/afollestad/material-dialogs.svg)](https://travis-ci.org/afollestad/material-dialogs)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0a4acc30a9ce440087f7688735359bb8)](https://www.codacy.com/app/drummeraidan_50/material-dialogs?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=afollestad/material-dialogs&amp;utm_campaign=Badge_Grade)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

---

![Screenshots](https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/showcase3.png)

# Modules

The core module is the fundamental module that you need in order to use this library. The others 
are extensions to core.

## Core

[ ![Core](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:core.svg?label=core) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Acore/_latestVersion)

#### [Core Tutorial and Samples](documentation/CORE.md)

The `core` module contains everything you need to get started with the library. It contains all
core and normal-use functionality.

<img src="https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/basic_with_buttons.png" width="200px" />

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:core:3.0.0-alpha1'
}
```

## Input

[ ![Input](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:input.svg?label=input) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Ainput/_latestVersion)

#### [Input Tutorial and Samples](documentation/INPUT.md)
 
The `input` module contains extensions to the core module, such as a text input dialog.

<img src="https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/input.png" width="200px" />

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:input:3.0.0-alpha1'
}
```
 
## Files

[ ![Files](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:files.svg?label=files) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Afiles/_latestVersion)

#### [Files Tutorial and Samples](documentation/FILES.md)

The `files` module contains extensions to the core module, such as a file and folder chooser.

<img src="https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/file_chooser.png" width="200px" />

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:files:3.0.0-alpha1'
}
```

## Color

[ ![Color](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:color.svg?label=color) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Acolor/_latestVersion)

#### [Color Tutorial and Samples](documentation/COLOR.md)

The `color` module contains extensions to the core module, such as a color chooser.

<img src="https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/color_chooser.png" width="200px" />

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:color:3.0.0-alpha1'
}
```

## DateTime

[ ![DateTime](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:datetime.svg?label=datetime) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Adatetime/_latestVersion)

#### [DateTime Tutorial and Samples](documentation/DATETIME.md)

The `datetime` module contains extensions to make date, time, and date-time picker dialogs.

<img src="https://raw.githubusercontent.com/afollestad/material-dialogs/master/art/datetimepicker.png" width="400px" />

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:datetime:3.0.0-alpha1'
}
```

## Lifecycle

[ ![Lifecycle](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:lifecycle.svg?label=lifecycle) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Alifecycle/_latestVersion)

#### [Lifecycle Tutorial and Samples](documentation/LIFECYCLE.md)

The `lifecycle` module contains extensions to make dialogs work with AndroidX lifecycles.

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:lifecycle:3.0.0-alpha1'
}
```

## Bottom Sheets

[ ![Lifecycle](https://img.shields.io/bintray/v/drummer-aidan/maven/material-dialogs:bottomsheets.svg?label=bottomsheets) ](https://bintray.com/drummer-aidan/maven/material-dialogs%3Abottomsheets/_latestVersion)

#### [Bottom Sheets Tutorial and Samples](documentation/BOTTOMSHEETS.md)

The `bottomsheets` module contains extensions to turn modal dialogs into bottom sheets, among 
other functionality like showing a grid of items. Be sure to checkout the sample project for this,
too!

```gradle
dependencies {
  ...
  implementation 'com.afollestad.material-dialogs:bottomsheets:3.0.0-alpha1'
}
```
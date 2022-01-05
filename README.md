# 👏 Gallery Collapse [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://opensource.org/licenses/MIT)

<p align="center"> 
<img src="https://github.com/ThuyenPV/resource-repo/blob/main/gallery_collapse/gif/d8cd7ffd0da549ce64bc55e81254e1d9.gif" height="600" alt="Screenshot">
<img src="https://github.com/ThuyenPV/resource-repo/blob/main/gallery_collapse/gif/2344a80c0576c4ee33dd8089a5a03590.gif" height="600" alt="Screenshot">
</p>

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://ko-fi.com/zuyenz)

<p>A flutter package which display the library collapse according to the number of images associated with hero animation ...</p>

The source code is **100% Dart**, and everything resides in the [/lib](https://github.com/xsahil03x/giffy_dialog/tree/master/lib) folder.

# 🔅 Gifs

|                                                                                                                                                          |                                                                                                                                                          |                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/ThuyenPV/resource-repo/blob/main/gallery_collapse/gif/06e08b7805562c84edc9b2d57117a900.gif" height="400" alt="Screenshot"/> | <img src="https://github.com/ThuyenPV/resource-repo/blob/main/gallery_collapse/gif/0bc449b8e06aee0c121872e2e94109b1.gif" height="400" alt="Screenshot"/> | <img src="https://github.com/ThuyenPV/resource-repo/blob/main/gallery_collapse/gif/581a7e66420a8405c4b1ee8228ca967d.gif" height="400" alt="Screenshot"/> |
|                                                                                                                                                          |                                                                                                                                                          |                                                                                                                                                          |

# 💻 Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

[![Version](https://img.shields.io/pub/v/before_after.svg)](https://pub.dartlang.org/packages/before_after)

```yaml
dependencies:
  gallery_collapse: <latest version>
```

# ❔ Usage

### Import this class

```dart
import 'package:image_collapse/image_collapse.dart';
```

### before after

```dart
    ImageCollapse(
        imageUrls: listNetworkImages,
    ),
```

## 🎨 Customization and Attributes

All customizable attributes for BeforeAfter Widget

<table>
    <th>Attribute Name</th>
    <th>Example Value</th>
    <th>Description</th>
    <tr>
        <td>imageUrls (List<String>)</td>
        <td>['https://pub.dev/flutter_logo.png']</td>
        <td>Sets List Images From Network</td>
    </tr>
    <tr>
        <td>titleGallery (String?)</td>
        <td>Gallery</td>
        <td>Title display when click to a image image</td>
    </tr>
    <tr>
        <td>remainNumberStyle (TextStyle?)</td>
        <td>false</td>
        <td>Set style for the remaining number of images</td>
        </tr>
    <tr>
        <td>crossAxisCount (int)</td>
        <td>6.0</td>
        <td>Set crossAxisCount between images</td>
    </tr>
    <tr>
        <td>mainAxisSpacing (double)</td>
        <td>4.0</td>
        <td>Set mainAxisSpacing between images</td>
    </tr>
    <tr>
        <td>crossAxisSpacing (double)</td>
        <td>4.0</td>
        <td>Set crossAxisSpacing between images</td>
    </tr>
    <tr>
        <td>backgroundImageView (BoxDecoration?)</td>
        <td> BoxDecoration(color: Color(0xff374056))</td>
        <td>Set the background color for the image when clicked show</td>
    </tr>
      <tr>
        <td>fadingColorCollapse (Color?)</td>
        <td>16.0</td>
        <td>Set background color for remaining number of images</td>
    </tr>
      <tr>
        <td>appBarColor (Color?)</td>
        <td>Colors.yellow</td>
        <td>Set color for appBar when displaying image</td>
    </tr>
    
</table>

# 👍 How to Contribute

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## Getting Started

For help getting started with Flutter, view our online [documentation](https://flutter.io/).

For help on editing package code, view the [documentation](https://flutter.io/developing-packages/).

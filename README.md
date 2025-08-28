# Flutter Gradient App Bar
> This is a fork of [flutter_gradient_app_bar](https://github.com/shawn-grant/FlutterGradientAppBar), but with Flutter 3.35/Dart 3 support. If you're still using Flutter 3.x < 3.34, use the original package.
 
Love the material AppBar? Do you want to add more color to the appbar? Here's a GradientAppBar.

It works just like the normal AppBar. Also with actions, back buttons, titles. So it's just your normal AppBar, but with a twist!

## Screenshots

![image](https://user-images.githubusercontent.com/7083755/43866104-e9bc98ea-9b64-11e8-9115-b2deec915dbd.png)
![image](https://user-images.githubusercontent.com/7083755/43866237-4f8e6a5e-9b65-11e8-8adf-2514a9b1e10c.png)


## Getting Started

1. Install the dependency:
```
  $ flutter pub add flutter_gradient_app_bar_plus
```

4. Import the package: 
```
import 'package:flutter_gradient_app_bar/flutter_gradient_app_bar_plus.dart'
```

5. Replace your Scaffold AppBar with GradientAppBar.
```dart
appBar: GradientAppBar(
  title: Text('Flutter'),
  gradient: LinearGradient(
    colors: [Colors.blue, Colors.purple, Colors.red],
  ),
),
```



# Gradient App Bar
> NB: This is a fork of [new_gradient_app_bar](https://github.com/GUIKAR741/NewGradientAppBar), but with Flutter 3.10/Dart 3 support
 
Love the material AppBar? Do you want to add more color to the appbar? Here's a GradientAppBar.

It works just like the normal AppBar. Also with actions, back buttons, titles. So it's just your normal AppBar, but with a twist!

## Screenshots

![image](https://user-images.githubusercontent.com/7083755/43866104-e9bc98ea-9b64-11e8-9115-b2deec915dbd.png)
![image](https://user-images.githubusercontent.com/7083755/43866237-4f8e6a5e-9b65-11e8-8adf-2514a9b1e10c.png)


## Getting Started

1. Depend on it by adding this to your pubspec.yaml file:
   ```
   flutter_gradient_app_bar:
    git:
      url: https://github.com/shawn-grant/FlutterGradientAppBar.git
      ref: master
   ```

4. Import it: ```import 'package:flutter_gradient_app_bar/flutter_gradient_app_bar.dart'```

5. Replace your current AppBar (In the scaffold) to GradientAppBar. 


```
appBar: GradientAppBar(
    title: Text('Flutter'),
    gradient: LinearGradient(colors: [Colors.blue, Colors.purple, Colors.red])
  ),
```



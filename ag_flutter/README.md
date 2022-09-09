# Notes

> The `runApp()` function sets up the initial settings for the app and defines which is the root widget of the application.
>
> **_The framework forces the root widget to cover all the screen_**. Our root widget is the `MaterialApp` widget.
>
> The word `Widget` refers to any object that shows on the screen, or helps to show objects on the screen.

## Sample Code

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        body: Center(
          child: Text(
            'Hello World!',
          ),
        ),
      ),
    ),
  );
}
```

## Important Links

| Topic                      | Link                                                     |
| -------------------------- | -------------------------------------------------------- |
| Material Component Widgets | https://flutter.dev/docs/development/ui/widgets/material |

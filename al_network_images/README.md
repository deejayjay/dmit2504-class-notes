# Notes

> The `Image.network()` named constructor creates a widget that displays an `[ImageStream]` obtained from the network.

## Sample Code

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.blueGrey,
        appBar: AppBar(
          title: const Text("Stateless Widget with Network Image"),
          backgroundColor: Colors.blueGrey[900],
        ),
        body: Center(
          child:
              Image.network('https://www.w3schools.com/w3css/img_snowtops.jpg'),
        ), // Center
      ), // Scaffold
    ); // MaterialApp
  }
}

```

## Important Links

| Topic                              | Link                                        |
| ---------------------------------- | ------------------------------------------- |
| Images Widget - Widget of the Week | https://www.youtube.com/watch?v=7oIAs-0G4mw |

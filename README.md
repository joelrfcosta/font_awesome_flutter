# font_awesome_flutter

The [Font Awesome](http://fontawesome.io/icons/) Icon pack available as set of Flutter Icons.

Based on Font Awesome 5.3.0. Includes all free icons:

  * Regular
  * Solid
  * Brands

## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
  font_awesome_flutter: <latest_version>
```

## Usage

```dart
import 'package:font_awesome_flutter/font_awesome_flutter.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      // Use the FontAwesomeIcons class for the IconData
      icon: new Icon(FontAwesomeIcons.gamepad), 
      onPressed: () { print("Pressed"); }
     );
  }
}
```

## Example

View the Flutter app in the `example` directory to see all the available `FontAwesomeIcons`.

## Contributors

  - Brian Egan
  - Phil Plante

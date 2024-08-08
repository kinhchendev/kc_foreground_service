# KC Foreground Service
## Latest version 0.0.1
## Setup

### Step 1
Add the plugin to your pubspec.yaml file:

````yaml
dependencies:
  flutter:
    sdk: flutter
  kc_foreground_service: ^LATEST_VERSION_HERE
````

Replace the `LATEST_VERSION_HERE` the latest version number as stated on this page.

### Step 2
Import the package into your project

```dart
import 'package:kc_foreground_service/kc_foreground_service.dart';
```

## Usage
In essence, the following line of code will start the foreground service:

````dart
await ForegroundService().start();
````

To stop the service again, use the following line of code:

````dart
await ForegroundService().stop();
````
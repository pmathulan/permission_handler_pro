# permission_handler_platform_interface_pro

A common platform interface for the `permission_handler_pro` plugin. Published by **SiTechra (Pvt) Ltd**.

This package is a specialized fork of the official `permission_handler_platform_interface` package by [Baseflow](https://baseflow.com).

## Usage

This interface allows platform-specific implementations of the `permission_handler_pro` plugin, as well as the plugin itself, to ensure they support the same interface.

To implement a new platform-specific implementation, extend `PermissionHandlerPlatform` and set the default instance:
```dart
PermissionHandlerPlatform.instance = MyPlatformPermissionHandler();
```

## Credits & Attribution

This package is built upon the excellent work by the original authors at [Baseflow](https://baseflow.com).
- Original Package: [permission_handler_platform_interface](https://pub.dev/packages/permission_handler_platform_interface)
- Original Repository: [flutter-permission-handler](https://github.com/Baseflow/flutter-permission-handler)

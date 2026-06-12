# permission_handler_pro

A suite of packages providing a cross-platform API to request and check permissions in Flutter. Published by **SiTechra (Pvt) Ltd**.

This suite is a specialized fork of the official [permission_handler](https://pub.dev/packages/permission_handler) package by [Baseflow](https://baseflow.com), updated for compatibility with the latest build toolchains (including MSVC / Visual Studio 2022/v17/v18).

The suite is built using a federated plugin architecture and is divided into the following packages:

1. [`permission_handler_pro`](./permission_handler): The app-facing package that users depend on in their projects.
2. [`permission_handler_platform_interface_pro`](./permission_handler_platform_interface): Declares the interface all platform packages must implement.
3. [`permission_handler_android_pro`](./permission_handler_android): Android implementation.
4. [`permission_handler_apple_pro`](./permission_handler_apple): iOS/macOS implementation.
5. [`permission_handler_html_pro`](./permission_handler_html): Web implementation.
6. [`permission_handler_windows_pro`](./permission_handler_windows): Windows implementation.

## Attribution

We want to extend our sincere gratitude to [Baseflow](https://baseflow.com) and the contributors of the original [permission_handler](https://pub.dev/packages/permission_handler) package. Their outstanding work forms the core of this library.

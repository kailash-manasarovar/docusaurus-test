**[Unreal GDK version 0.9.0 is go!](https://github.com/spatialos/UnrealGDK/releases/tag/0.10.0)**

## Release Notes

### Performance
We have made significant performance improvements to the GDK to reduce latency, egress and CPU use. 

We have also introduced a new SpatialOS Runtime variant called Standard, which is now the default Runtime for the GDK. You can change back to the Compatibility Mode Runtime variant if you need to. 

### Mobile Support: Android and iOS [Preview]
Android and iOS are now in [preview](https://documentation.improbable.io/gdk-for-unreal/docs/product-maturity-lifecycle). We support workflows for developing and doing in-studio playtests on Android and iOS devices, and have documentation for these workflows. We also support macOS (also in preview) for developing and testing iOS game clients. We’d love to hear your feedback on this!

### User Experience 
- We have introduced a new [tutorial](https://documentation.improbable.io/gdk-for-unreal/docs/multiserver-offloading-introduction) to take you through how to use multiserver offloading, using a new game mode in the Example Project.
- You can now fully build and deploy to the cloud without leaving the Unreal Editor. The `Start Deployment` button in the `Cloud Deployment Configuration` dialog box now generates schema and a snapshot, builds all selected workers, and uploads the assembly before starting the deployment. 
- In the `Cloud Deployment Configuration` dialog box you can generate a launch configuration file from the current map, or you can click through to the `Launch Configuration Editor`.
- Full Scan schema generation now uses the `CookAndGenerateSchema` commandlet, which results in faster and more stable schema generation for big projects.
- We have created a new drop-down menu in the GDK toolbar to configure how to connect your PIE client or your Launch on Device client.

…and much more! For the full details on what’s new in this release, including bug fixes, see the [0.10.0 changelog](https://github.com/spatialos/UnrealGDK/blob/0.10.0/CHANGELOG.md).

### SpatialOS Tooling Compatibility
If you're using the Standard Runtime variant, there are several compatibility issues. For more information, see [the changelog](https://github.com/spatialos/UnrealGDK/blob/0.10.0/CHANGELOG.md#spatialos-tooling-compatibility).

### Known Issues
Please see the full list of known issues in this release [here](https://github.com/spatialos/UnrealGDK/blob/0.10.0/CHANGELOG.md#spatialos-tooling-compatibility).

## Upgrading
The corresponding **Engine** versions are:

**[4.24-SpatialOSUnrealGDK-0.10.0](https://github.com/improbableio/UnrealEngine/releases/tag/4.24-SpatialOSUnrealGDK--0.10.0)** (primary UE version)

**[4.23-SpatialOSUnrealGDK-0.10.0](https://github.com/improbableio/UnrealEngine/releases/tag/4.23-SpatialOSUnrealGDK-0.10.0)** ([legacy](https://documentation.improbable.io/gdk-for-unreal/docs/versioning-scheme#section-unreal-engine-version-support) UE version)

The corresponding **Example Project** version is:

**[0.10.0](https://documentation.improbable.io/gdk-for-unreal/docs/versioning-scheme#section-unreal-engine-version-support)**

Follow **[these](https://documentation.improbable.io/gdk-for-unreal/docs/keep-your-gdk-up-to-date)** steps to upgrade your GDK, Engine fork and Example Project to the latest release.

Happy developing,

*The GDK team*

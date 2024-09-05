# GoogleCast Without Bluetooth

Dynamic Linked Version.

References:

- https://developers.google.com/cast/docs/ios_sender#xcframework
- https://developers.google.com/cast/docs/ios_sender#manual_setup

Use always **DYNAMIC** version for this repository.

## Version

Current version is: `4.8.3`

You can confirm here: `GoogleCast.xcframework/ios-arm64/GoogleCast.framework/Headers/GCKDefines.h` on variables:

```cxx
#define GCK_VERSION_MAJOR X
#define GCK_VERSION_MINOR X
#define GCK_VERSION_FIX X
```

## How to update

Always delete `GoogleCast.xcframework` folder and put the new folder.

After, test pod using `pod spec lint`.

Finally, change version name inside README file and PODSPEC file.

## License

This is only a copy of official Google framework and Cocoapods tool files. Check their licenses.

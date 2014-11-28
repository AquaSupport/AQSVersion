AQSVersion
==========

Version constants manager for easier stubbing App Version, iOS Version.

```objc
AQSAppVersion *appVersion = [AQSVersion appVersion];

AQSOSVersion *version = [AQSVersion osVersion];
```

```objc
// AQSAppVersion

@property NSUInteger majorVersion;
@property NSUInteger minorVersion;
@property NSUInteger patchVersion;
```

```objc
// AQSOSVersion

@property NSUInteger majorVersion;
@property NSUInteger minorVersion;
@property NSUInteger patchVersion;
```

And setters for debugging.

```
[AQSVersion setAppVersion:appVersion];

[AQSVersion setOSVersion:osVersion];
```

# fl_responsive_ui

- add this code in main.dart Widget to update UI when screen size change.
```
final screeSize = MediaQuery.of(context).size;
    FlResponsiveUI().updateScreenDimension(
        width: screeSize.width, height: screeSize.height);
```

- for responsive width
```
// 170.0 is your desire width value
FlResponsiveUI().getProportionalWidth(width: 170.0)
```

- for responsive height
```
// 70.0 is your desire height value
FlResponsiveUI().getProportionalHeight(height: 70.0)
```
- for Regular TextStyle for responsive text
```
// can set fontSize, color, isChangeAccordingToDeviceSize,
// characterSpacing and lineSpacing
FlResponsiveUI().getTextStyleRegular(
  fontSize: 18
)
```

- for orientation
```
// to check device orientation
// this is optional
// You can get orientation by MedaiQuery in flutter
FlResponsiveUI().getDeviceOrientation(context)
```

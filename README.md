# TouchesWindow
Show touch and force-touch indicators for your iOS app. Have swift and obj-c versions

# How to use in swift

1) Copy and paste `DMZTouchesWindow.swift` to your project

2) Use in your project:

```swift
let window = DMZTouchesWindow(frame: UIScreen.main.bounds);
window.dmz_touchesEnabled = true
...
```

# How to use in objc

1) Copy and paste files `DMZTouchesWindow.h`, `DMZTouchesWindow.m` to your project

2) Use in your project:

```objc
DMZTouchesWindow *window = [[DMZTouchesWindow alloc] initWithFrame:UIScreen.mainScreen.bounds];
window.dmz_touchesEnabled = YES;
...
```

# How it looks
![alt tag](https://github.com/dmoroz0v/TouchesWindow/blob/master/DMZTouchesWindowSample/HowItLooks.png)

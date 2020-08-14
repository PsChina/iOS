# iOS
iOS 开发中遇到的坑


swift 找不到根控制器

```swift
 var rootViewController = UIApplication.shared.keyWindow?.rootViewController;
  while let presentedViewController = rootViewController?.presentedViewController {
     rootViewController = presentedViewController
 }
```

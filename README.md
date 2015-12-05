# Tutorial Sample Code: How to implement FBLogin in Xcode7 and Swift

Recording some bugs and suggestions when I practice [Facebook Login in Swift - Xcode 6.3 iOS 8.3 Tutorial](https://www.youtube.com/watch?v=cpANieebE2M)

Chinese Version:  
http://waynechu.logdown.com/posts/344138-ios-fb-login-swift

## Environments

* Xcode: Version 7.1.1
* Language: Apple Swift version 2.1

## Tutorial：

https://www.youtube.com/watch?v=cpANieebE2M

## Suggestions & Bugs

### Suggestions

* You can follow facebook's quick start to set FB App settings, just go to `Get Started with the Facebook SDK` -> `Choose Platform` -> `iOS`, and copy paste all `info.plist` stuffs and `Bundle Identifier` and then you can skip the quick start tutorial.

### Bugs

* You need to checked `copy item if needed` when you importing FB SDK into your project if you are using Xcode 7 and above, or you'll see `No such module FBSDKCoreKit` error. [StackOverflow](http://stackoverflow.com/questions/32096787/no-such-module-fbsdkcorekit-error)
* You should add your `Bundle Identifier` into you FB App Settings. If you havn't add iOS platform into you FB App, you should check my suggestion 1.



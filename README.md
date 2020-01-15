![](assets/header.jpg)

When you decide to use VIPER architecture in your project, it is very tired create new modules, because you need create at least 5 files for each. Imagine that you need to create 6 modules...I was suffering this problem, and this is the raison why I've created this template. It's very useful for me and I hope that for you too.

## How to install

### Using script (easy)
Only need execute this command in terminal:
```swift
sudo swift install.swift
```
You should be this output message:

![](assets/terminal.png)

If all it's ok you now could find your template in Xcode.

### Manual
Go to Application folder, browse to the Xcode application icon. Right-click it and choose 'Show Package Contents'. Then browse to:
`Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/Project Templates/iOS/Application` and add "Module VIPER.xctemplate" file. Now you can find your template in Xcode.

## Easy to use
![](/assets/wizard.png)

## Generated code
This template generates all files that you need to create a new VIPER module. All generated code is Swift 4.

This is an example, we're creating a Login module:

- [Default, without divide](/assets/defaultOutput.md)
- [With divided Interactor (Input & Output)](/assets/inputOutput.md)

## VIPER diagram overview
![Preview](/assets/viper_diagram.png)

## References
- [iOS Architecture Patterns](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.ba7q8dcih)
- [#8 VIPER to be or not to be?](https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/)
- [https://www.objc.io/issues/13-architecture/viper/](https://www.objc.io/issues/13-architecture/viper/)
- [https://www.ckl.io/blog/ios-project-architecture-using-viper/](https://www.ckl.io/blog/ios-project-architecture-using-viper/)

## Author

* Thomas Droin

## Inspired by

* Juanpe Catalán - https://github.com/Juanpe/Swift-VIPER-Module

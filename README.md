# AMCodeView

[![Version](https://img.shields.io/cocoapods/v/AMCodeView.svg?style=flat)](https://cocoapods.org/pods/AMCodeView)
[![License](https://img.shields.io/cocoapods/l/AMCodeView.svg?style=flat)](https://cocoapods.org/pods/AMCodeView)
[![Platform](https://img.shields.io/cocoapods/p/AMCodeView.svg?style=flat)](https://cocoapods.org/pods/AMCodeView)

## Preview

<img src="https://raw.githubusercontent.com/Davarg/ReadmeFiles/0ca443d49f92a2e1d9bc302fed878fb59f4adbd9/AMCodeView/first.png" width="214"/> <img src="https://raw.githubusercontent.com/Davarg/ReadmeFiles/0ca443d49f92a2e1d9bc302fed878fb59f4adbd9/AMCodeView/second.png" width="214"/>

## Requirements
iOS >= 10

## Using
1. Create view: 
```objective-c
AMCodeView *view = [[AMCodeView alloc] init];
```
2. Configure it:
```objective-c
AMCodeViewConfiguration *config = [AMCodeViewConfiguration defaultConfig];
config.isUnderlineFilled = YES;
[view configure:config];
```
3. Start responder: 
```objective-c
AMCodeViewResponder *responder = [[AMCodeViewResponder alloc] initWithConfig:config viewResponsible:view];
responder.delegate = self;
```

## Installation

AMCodeView is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'AMCodeView'
```

## Author

Davarg, maka-dava@yandex.ru

## License

AMCodeView is available under the MIT license. See the LICENSE file for more info.

RMDateSelectionViewController ![Build Status](https://travis-ci.org/CooperRS/RMDateSelectionViewController.svg?branch=master)
=============================

This is an iOS control for selecting a date using UIDatePicker in a UIActionSheet like fashion

## Screenshots
### Portrait
![Portrait](http://cooperrs.github.io/RMDateSelectionViewController/Images/Blur-Screen-Portrait.png)

### Landscape
![Landscape](http://cooperrs.github.com/RMDateSelectionViewController/Images/Blur-Screen-Landscape.png)

### Black version
![Colors](http://cooperrs.github.io/RMDateSelectionViewController/Images/Blur-Screen-Portrait-Black.png)

## Demo Project
If you want to run the demo project you first need to run `pod install` to install the dependencies of RMDateSelectionViewController.

## Installation (CocoaPods)
```ruby
platform :ios, '8.0'
pod "RMDateSelectionViewController", "~> 2.0.3"
```

## Usage

See the [Wiki Pages](https://github.com/CooperRS/RMDateSelectionViewController/wiki) on how to use RMDateSelectionViewController. Also take a look at [Migration](https://github.com/CooperRS/RMDateSelectionViewController/wiki/Migration) on how to migrate to the latest version of RMDateSelectionViewController.

## Documentation
There is an additional documentation available provided by the CocoaPods team. Take a look at [cocoadocs.org](http://cocoadocs.org/docsets/RMDateSelectionViewController/).

## Requirements

| Compile Time  | Runtime       |
| :------------ | :------------ |
| Xcode 7       | iOS 8         |
| iOS 9 SDK     |               |
| ARC           |               |

Note: ARC can be turned on and off on a per file basis.

Version 1.5.0 and above of RMDateSelectionViewController use custom transitions for presenting the date selection controller. Custom transitions are a new feature introduced by Apple in iOS 7. Unfortunately, custom transitions are totally broken in landscape mode on iOS 7. This issue has been fixed with iOS 8. So if your application supports landscape mode (even on iPad), version 1.5.0 and above of this control require iOS 8. Otherwise, iOS 7 should be fine. In particular, iOS 7 is fine for version 1.4.3 and below.

## Apps using this control
Using this control in your app or know anyone who does?

Feel free to add the app to this list: [Apps using RMDateSelectionViewController](https://github.com/CooperRS/RMDateSelectionViewController/wiki/Apps-using-RMDateSelectionViewController)

## Further Info
If you want to show an UIPickerView instead of an UIDatePicker, you may take a look at my other control called [RMPickerViewController](https://github.com/CooperRS/RMPickerViewController).

If you want to show any other control you may want to take a look at [RMActionController](https://github.com/CooperRS/RMActionController).

##Credits
Code contributions:
* AnthonyMDev
    * Cancel delegate method should be optional
* Digeon Benjamin 
    * Delegate method when now button is pressed
    * Cancel delegate method is called when background view is tapped
* Denis Andrasec
    * Bugfixes
* Robin Franssen
	* Block support
* Scott Chou
    * Images for cancel and select button
* steveoleary
	* Bugfixes

Localizations:
* Vincent Xue (Chinese)
* Alex Studnička (Czech)
* Robin Franssen (Dutch)
* tobiasgr (Danish)
* Thomas Besnehard (French)
* Heberti Almeida (Portuguese)
* Anton Rusanov (Russian)
* Pedro Ventura (Spanish)
* Aron Manucheri (Swedish)
* Vinh Nguyen (Vietnamese)

I want to thank everyone who has contributed code and/or time to this project!

## License (MIT License)
Copyright (c) 2013-2015 Roland Moers

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

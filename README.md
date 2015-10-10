# Swift Based UI Demo
This repository consist small Xcode project for various UI element used within iOS application. All sample build in such a way that you will get clear idea how to use practically each UI Element within swift based application. You can use this free for personal or commercial use.

### Platform & Supported Device
+ Swift 2, Xcode 7, iOS 9
+ iPhone 4s, 5, 5s, 5c, 6, 6 Plus, 6s, 6s Plus, all iPad having iOS 9.

## Index
+ Demo-1: [UILabel](#demo-1-uilabel)
+ Demo-2: [UIButton](#demo-2-uibutton)
+ Demo-3: [UISegmentedControl](#demo-3-uisegmentedcontrol)
+ Demo-4: [UITextField](#demo-4-uitextfield)
+ Demo-5: [UITextView](#demo-5-uitextview)
+ Demo-6: [UISlider](#demo-6-uislider)
+ Demo-7: [UISwitch](#demo-7-uiswitch)
+ Demo-8: [UIActivityIndicatorView](#demo-8-uiactivityindicatorview)
+ Demo-9: [UIProgressView](#demo-9-uiprogressview)
+ Demo-10: [UIStepper](#demo-10-uistepper)
+ Demo-11: [UIImageView](#demo-11-uiimageview)
+ Demo-12: [UIScrollView](#demo-12-uiscrollview)
+ Demo-13: [UIDatePicker](#demo-13-uidatepicker)
+ Demo-14: [UIPickerView](#demo-14-uipickerview)
+ Demo-15: [UIView](#demo-15-uiview)
+ Demo-16: [UIContainerView](#demo-16-uicontainerview)
+ Demo-17: [UIVisualEffectView](#demo-17-uivisualeffectview)
+ Demo-18: [UIAlertController](#demo-18-uialertcontroller)
+ Demo-19: [UIWebView](#demo-19-uiwebview)
+ Demo-20: [UINavigationBar](#demo-20-uinavigationbar)
+ Demo-21: [UITabBar](#demo-21-uitabbar)
+ Demo-22: [UITableView](#demo-22-uitableview)
+ Demo-23: [UICollectionView](#demo-23-uicollectionview)
+ Demo-24: [UIToolbar](#demo-24-uitoolbar)
+ Demo-25: UISearchBar
+ Demo-26: UIStackView - Horizontal
+ Demo-27: UIStackView - Vertical
+ Demo-28: UITapGestureRecognizer
+ Demo-29: UIPinchGestureRecognizer
+ Demo-30: UIRotationGestureRecognizer
+ Demo-31: UISwipeGestureRecognizer
+ Demo-32: UIPanGestureRecognizer
+ Demo-33: UIScreenEdgePanGestureRecognizer
+ Demo-34: UILongPressGestureRecognizer


## Demo-1: UILabel
Sample project that demonstrate how to use Label.

![ScreenShot](../master/Screenshots/demo1-1t.png)
![ScreenShot](../master/Screenshots/demo1-2t.png)

## Demo-2: UIButton
Sample project that demonstrate how to use Button.

![ScreenShot](../master/Screenshots/demo2-1t.png)
![ScreenShot](../master/Screenshots/demo2-2t.png)

## Demo-3: UISegmentedControl
Sample project that demonstrate how to use Segmented Control.

![ScreenShot](../master/Screenshots/demo3-1t.png)
![ScreenShot](../master/Screenshots/demo3-2t.png)

## Demo-4: UITextField
Sample project that demonstrate how to use UITextField with delegate, close keyboard when clicked anywhere on the screen, move editing from one text field to next text field when Next button clicked within keyboard.

![ScreenShot](../master/Screenshots/demo4-1t.png)
![ScreenShot](../master/Screenshots/demo4-2t.png)

## Demo-5: UITextView
Sample project demonstrate how to use UITextView that allows multi line editing and support newline character. This demo also shows how to close the keyborad by placing action within UIButton (Note: Return key within keyboard will not close the keyboard for textview becuase return key will add newline "\n" character). Newline character support must for UITextView due it's usage for long text having paragraph, so we must close keyboard by any other way that appropriate.

![ScreenShot](../master/Screenshots/demo5-1t.png)
![ScreenShot](../master/Screenshots/demo5-2t.png)

## Demo-6: UISlider
Sample project demonstrate how to use UISlider within swift based application. It shows how to read slider value and use it for changing font size etc.

![ScreenShot](../master/Screenshots/demo6-1t.png)
![ScreenShot](../master/Screenshots/demo6-2t.png)

## Demo-7: UISwitch
Sample project demonstrate how to use UISwitch, set various properties or value for UITextLabel based on UISwitch toggle status.

![ScreenShot](../master/Screenshots/demo7-1t.png)
![ScreenShot](../master/Screenshots/demo7-2t.png)

## Demo-8: UIActivityIndicatorView
Sample project demonstrate how to use UIActivityIndicatorView. i.e. How to Start/Stop spinning programmatically and hide it.

![ScreenShot](../master/Screenshots/demo8-1t.png)
![ScreenShot](../master/Screenshots/demo8-2t.png)

## Demo-9: UIProgressView
Sample project demonstrate how to use UIProgressView. i.e. how to increment progress programmaticaly, reset it etc. Used NSTimer for auto increment progress at certain interval. This example also demonstrate how to use NSTimer practically.

![ScreenShot](../master/Screenshots/demo9-1t.png)
![ScreenShot](../master/Screenshots/demo9-2t.png)

## Demo-10: UIStepper
Sample project demonstrate how to use UIStepper for increment counter and font size at run time. 

![ScreenShot](../master/Screenshots/demo10-1t.png)
![ScreenShot](../master/Screenshots/demo10-2t.png)

## Demo-11: UIImageView
Sample project that demonstrate how to use UIImageView and set ContentMode runtime. (e.g. ``ScaleToFill``, ``ScaleAspectFit``, ``ScaleAspectFill``, ``Redraw``, ``Center``, ``Top``, ``Bottom``, ``Left``, ``Right``, ``TopLeft``, ``TopRight``, ``BottomLeft``, ``BottomRight``).

![ScreenShot](../master/Screenshots/demo11-1t.png)
![ScreenShot](../master/Screenshots/demo11-2t.png) 

![ScreenShot](../master/Screenshots/demo11-3t.png)
![ScreenShot](../master/Screenshots/demo11-4t.png)

## Demo-12: UIScrollView
Sample project demonstrate how to use UIScrollView. i.e. How to set scroll view content size, content offset, zoom scale etc. It shows how to add UIImageView runtime and set Default, Minimum, and Maximum Zoom scale. It's using UIScrollViewDelegate method for detecting zoom.

![ScreenShot](../master/Screenshots/demo12-1t.png)
![ScreenShot](../master/Screenshots/demo12-2t.png)

## Demo-13: UIDatePicker
Sample project demonstrate how to use UIDatePicker i.e. read date value and assign to label when user change it runtime.

![ScreenShot](../master/Screenshots/demo13-1t.png)
![ScreenShot](../master/Screenshots/demo13-2t.png)

## Demo-14: UIPickerView
Sample project demonstrate how to use UIPickerView having custom component. It shows how to fillup data within each component using UIPickerViewDataSource and read selected component value at runtime.

![ScreenShot](../master/Screenshots/demo14-1t.png)
![ScreenShot](../master/Screenshots/demo14-2t.png)

## Demo-15: UIView
Sample project demonstrate how to use UIView and change its property (corner radious, border thickness) runtime using UISlider etc.

![ScreenShot](../master/Screenshots/demo15-1t.png)
![ScreenShot](../master/Screenshots/demo15-2t.png)

## Demo-16: UIContainerView
Sample project demonstrate how to use UIContainerView to load UIViewController within specific area of the screen. This demo also shows how to show/hide external view via UISegmentedControl and how external view behaves when navigate via bar button.

![ScreenShot](../master/Screenshots/demo16-1t.png)
![ScreenShot](../master/Screenshots/demo16-2t.png)

![ScreenShot](../master/Screenshots/demo16-3t.png)
![ScreenShot](../master/Screenshots/demo16-4t.png)

## Demo-17: UIVisualEffectView
Sample project demonstrate how to apply Blur and Vibrancy using UIVisualEffectView. It provides three options i.e. Extra Light, Light and Dark.

![ScreenShot](../master/Screenshots/demo17-1t.png)
![ScreenShot](../master/Screenshots/demo17-2t.png)

## Demo-18: UIAlertController
Sample project demonstrate how to show Alert and ActionSheet using UIAlertController having different action button i.e Ok, Cancel, Yes, No, Delete etc.

![ScreenShot](../master/Screenshots/demo18-1t.png)
![ScreenShot](../master/Screenshots/demo18-2t.png)


## Demo-19: UIWebView
Sample projet demonstrate how to load web url within UIWebView component. 

![ScreenShot](../master/Screenshots/demo19-1t.png)
![ScreenShot](../master/Screenshots/demo19-2t.png)


## Demo-20: UINavigationBar
Sample project demonstrate how to navigate screen using 'segue', It also shows how to set the title for the destination screen by overriding the prepareForSegue function.

![ScreenShot](../master/Screenshots/demo20-1t.png)
![ScreenShot](../master/Screenshots/demo20-2t.png)


## Demo-21: UITabBar
Sample project demonstrate how to implement tab based application flow using UITabBar. Contact screen consist top bar button (Map) that link with "Location Map" screen via segue and navigation controller.

![ScreenShot](../master/Screenshots/demo21-1t.png)
![ScreenShot](../master/Screenshots/demo21-2t.png)

![ScreenShot](../master/Screenshots/demo21-3t.png)
![ScreenShot](../master/Screenshots/demo21-4t.png)


## Demo-22: UITableView
Sample project demonstrate how to use UITableView. i.e. how to display multiple section and fillup data for each. When clicked on particular row, it will pass the selected item name to details view controller and item name displayed accordingly on details screen.

![ScreenShot](../master/Screenshots/demo22-1t.png)
![ScreenShot](../master/Screenshots/demo22-2t.png)

## Demo-23: UICollectionView
Sample project demonstrate how to use UICollectionView. i.e. Creating custom cell that consist image, change image corner radioous at runtime as when stepper value changed.

![ScreenShot](../master/Screenshots/demo23-1t.png)
![ScreenShot](../master/Screenshots/demo23-2t.png)

![ScreenShot](../master/Screenshots/demo23-3t.png)
![ScreenShot](../master/Screenshots/demo23-4t.png)

## Demo-24: UIToolbar
Sample project demonstrate how to use UIToolbar. UIToolbar can be used for various action button. This project also demonstrate how to show hide toobar using UIView Animation technique.

![ScreenShot](../master/Screenshots/demo24-1t.png)
![ScreenShot](../master/Screenshots/demo24-2t.png)

![ScreenShot](../master/Screenshots/demo24-3t.png)
![ScreenShot](../master/Screenshots/demo24-4t.png)

## Demo-25: UISearchBar
Coming soon

## Demo-26: UIStackView - Horizontal
Coming soon

## Demo-27: UIStackView - Vertical
Coming soon

## Demo-28: UITapGestureRecognizer
Coming soon

## Demo-29: UIPinchGestureRecognizer
Coming soon

## Demo-30: UIRotationGestureRecognizer
Coming soon

## Demo-31: UISwipeGestureRecognizer
Coming soon

## Demo-32: UIPanGestureRecognizer
Coming soon

## Demo-33: UIScreenEdgePanGestureRecognizer
Coming soon

## Demo-34: UILongPressGestureRecognizer
Coming soon


## Image Source
Images shown within sample are taken from unsplash and used for demo purpose only. I does not claim ownership over any images or icon used.

## License
SwiftUIDemo is available under the MIT license. See the LICENSE file for more info.


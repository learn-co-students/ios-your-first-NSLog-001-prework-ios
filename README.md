# Write Your First Program
For your first task in xcode, print something to the console!

Instructions
---
 1. open up the provided xcode project (**your-first-NSLog.xcodeproj**)
 * In your file organizer (panel on the left) look for a file named **FISAppDelegate.m**. In here is where you'll be writing your first line of Objective-C !
 * Look for this line:
 
   ```objc
   -(BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {
   ```
 This is where we'll be writing our code.
 * Type `NSLog(@"hello world");`on an empty line in this method (that is, inside the curly braces `{ ... }`). Don't forget the semi-colon! 
 * Now hit command+R on your keyboard and your program will run. 
 * Look at your console... your message should be showing!

Here's a helpful image if you're having trouble:
 
![](http://curriculum-content.s3.amazonaws.com/ios/ios-your-first-NSLog/your-first-nslog-screenshot.png)

Extra Info
---
The space we just put that code into is a *method*. You'll be writing many of your own methods, but for now we'll just use this one because it's included in every iOS app and allows us to input any custom actions we want before the app runs. 

# Your First NSLog()

## Objectives

1. Open and navigate an Xcode project file.
2. Print a message to the debug console during run time.

## Review

In the previous reading we surveyed the layout of Xcode's tools. For this first lab, you're going to open and explore the simplest of Xcode projects and write your first line of code—calling a function that prints a string to the debug console. You'll need to navigate to the correct file, edit the code in the editor area, and watch for the printout in the debug console.

## Instructions
---
 1. Open the provided Xcode project inside the lab's directory (`your-first-NSLog.xcodeproj`). Explore the different areas of Xcode that the reading just discussed.
 2. In your Project Navigator, look for the file named `FISAppDelegate.m` (this is the "i**m**plementation" file for the `FISAppDelegate` class). It's within this file that you'll be writing your first line of Objective-C ! Look for this block of code, it's where you'll be adding your first `NSLog()`:
 
   ```objc
   -(BOOL)application:(UIApplication *)application
       didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {
       
       // Hey!
       
       // write your code here!  :D
       
       return YES;
   }
   ```
   
 2. Type `NSLog(@"Hello, World!");` on an empty line within this method—that is, inside the curly braces `{ ... }` and before the `return` statement. **Top Tip:** *This is a statement. Don't forget the* `;` *("semi-colon") at the end of your line! It ends your statement.*

 3. Now hit `⌘R` on your keyboard and your program will run. The iOS Simulator should launch into a black screen. Nothing's wrong! We just haven't given it anything to display in this program so it loads as a black screen.
 4. Look at your debugger output console viewer... your message "Hello, world!" should have printed! Here's a helpful image if you're having trouble:
 
![](http://curriculum-content.s3.amazonaws.com/ios/ios-your-first-NSLog/your-first-nslog-screenshot.png)

**Note:** *The spot in the code you were directed to add your* `NSLog()` *is the standard override point in the* `AppDelegate` *at application launch. We'll explain more of what the means later, but just remember that if you're directed to write code in the* `AppDelegate`, *it will likely be in this spot.*

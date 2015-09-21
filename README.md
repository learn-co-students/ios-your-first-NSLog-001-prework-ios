# Your First `NSLog()`

## Objectives

1. Open and navigate an Xcode project file.
2. Print a message to the debug console during run time.

## Introduction

In the previous reading we surveyed the layout of Xcode's tools. For this first lab, you're going to open and explore the simplest of Xcode projects and write your first line of code—calling a function that prints a string to the debug console. You'll need to navigate to the correct file, edit the code in the editor area, and watch for the printout in the debug console.

## Instructions

 1 — Open the provided Xcode project inside the lab's directory (`open your-first-NSLog.xcodeproj`). Explore the different areas of Xcode that the reading just discussed.

 2 — In your Project Navigator, look for the file named `FISAppDelegate.m` (this is the "i**m**plementation" file for the `FISAppDelegate` class). Find the block comment inside the `application:didFinishLaunchingWithOptions:` method. It's here that you'll be writing your first `NSLog()`:
 
```objc
- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {

    /**
    
     * Hey! Write your code here! :D
     
     */
    
    // do not alter
    return YES;  //
}   ///////////////
```
   
 3 — Type `NSLog(@"Hello, World!");` on an empty line within this method—that is, inside the curly braces `{ ... }` and before the `return` statement. **Top Tip:** *This is a statement. Don't forget the* `;` *("semi-colon") at the end of your line! It ends your statement.*

 4 — Now hit `⌘` `R` on your keyboard and your program will run. The iOS Simulator should launch into a blank screen. Nothing's wrong! We just haven't given it anything to display in this program.
 
 5 — Look at your debugger output console viewer... your message "Hello, world!" should have printed! Here's a helpful image if you're having trouble:
 
![](https://curriculum-content.s3.amazonaws.com/ios/ios-your-first-NSLog/your-first-nslog-screenshot.png)

**Note:** *The spot in the code you were directed to add your* `NSLog()` *is the standard override point in the* `FISAppDelegate` *at application launch. We'll explain more of what the means later, but just remember that if you're directed to write code in the* `FISAppDelegate`, *it will likely be in this spot.*

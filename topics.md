# Course Topics

## Weekly

### Week 1
- Intro to VS2019/Xamarin
  - navigator area
  - editor area
  - utilities area
  - choosing a simulator
  - compiling and running
 - Xamarin Layout \ XAML
  - `StackLayout`, `Label`
  - parent/child - `Children.Add`
  - coordinate system
 - Animations
 - GestureRecognizers
 - Exercises
  - Hello RIT-1
- Intro to App Center

### Week 2
- XAML
  - Shell project type
  - Hot-loading
  - Navigation
- C#
  - arrays
  - dictionaries
  - lambda functions
  - async/await
  - File I/O and using JSON
  - variables - `var`
  - creating instances
  - Types: strings, floats, ints
  - explicit casting v. type interence
- Debugging
  - Regular Breakpoints
  - Exception Breakpoints
  - Conditional Breakpoints
  - Step In/Step Over/Continue
  - Stack Trace
  - Profiling
  - Throwing Exceptions
  - Debugger Console
- Setting up App Center
  
### Week 3
- Mobile App Design
  - Prototyping
  - Application Definition Statement
  - Navigation
    - Navigation Controllers - "Drill Down" with Detail Views
    - Tab Bar
    - iPad Split View
 - Creating a Custom Class - `Person.cs`
 - Model-View-ViewModel
   - model contains and validates the data
 - Data Binding
  - INotifyPropertyChanged
 - Re-write *Motivator* to become *MVC Motivator*
 - App Design Exercise:
   - "Magnetic Poetry" App
   
### Week 4
 - Review *Monster HW*
   - add `didSet` property observer
   - add `description` method via - `CustomStringConvertible` - https://developer.apple.com/documentation/swift/customstringconvertible
 - Review *Motivator MVVM Plus Bromides*
   - *nil coalescing operator* - `??` - is like a ternary operator for optionals 
   - random array elements
   - class extensions
   - use `enum` to get rid of "magic numbers" in your code
 - Project 1
   - Assign [Project 1](./assignments/project-1.md)
   - Form Groups
   - Topics needed for Project 1 - Deliverable #1:
     - Demo importing icons
     - Demo setting up a splash screen
     - Everything you need for completing checkpoints #1 & #2 is posted!
     
### Week 5
 - Topics needed for Project 1 - Deliverable #2:
   - Storyboard
     - autolayout
     - autoresizing
   - Tables
     - datasource prototcols
       - how many sections?
       - how many rows?
     - delegate protocols
       - row was tapped
   - ViewControllers
     - creating them in Storyboard
     - segues
     - sending data to a "child" view controller - `prepare(for segue: UIStoryboardSegue, sender: Any?) `
     - sending data to a "parent" view controller - `@IBAction func unwindToMain(segue:UIStoryboardSegue)`
   - Navigation bars
     - adding one to a VC (using Storyboard)
     - adding buttons to a Nav Bar (using Storyboard)
   - Other examples of delegation and protocols:
     - `CLLocation`
     - `UIPickerView`
     
### Week 6
 - Topics needed for Project 1 - Final Deliverable:
   - Save a snapshot of view
   - Share a snapshot of view
   - Singletons
   
   
### Week 7
 - Topics needed for Final Project Extras: 
   - Dependency Injection
   - `UIAppearance`
   - `Kinetic Realism` & `UIInterpolatingMotionEffect`
   
### Week 8
 
### Week 9

### Week 10

### Week 11

### Week 12

### Week 13

### Week 14
- Testing
 - Unit Testing
 - *UI Testing*


## All Topics
- Tools
  - Xcode
  - Playgrounds
- Swift Language Features and Concepts
  - Immutability
  - Type Inference
  - Type Safety
  - upcasts and downcasts
  - Optionals
  - guard
  - Do/Try/Catch
  - Designated Initializers and Convenience Initializers
- Software Design Patterns
  - Target-Action
  - MVC
  - Dependency Injection
  - MVVM
  - Notifications
  - Delegation and Protocols (Dynamic Dispatch)
  - Inheritance
  - Composition
  - Separation of Concern
  - Singleton
- Foundation Classes
  - NSString & NSMutableString
  - NSArray & NSMutableArray
  - NSDictionary & NSMutableDictionary
  - NSData
  - NSDate
- Cocoa Touch
  - Application Delegate & Lifecycle
  - Saving State in NSUserDefaults
  - UIView and its subclasses
- Other iOS Frameworks
  - AVFoundation
  - Core Location
  - Maps
  - CoreGraphics
  - SpiteKit or WatchKit
  - Profiling with Instruments
  - Core Animation Tool
- Leaks Tool
- Case Studies
  - CountR & Technobabble Generator & Tip Calculator
- Concepts explored:
- Storyboards
Target-Action
View Controllers
Writing Methods
Calling Methods on Foundation classes
Custom Classes
Magnet App
Concepts explored:
Arrays
Utilizing Camera (P1)
Storing Data (P1)
Sharing Content (P1)
Object Serialization (P1)
National Parks
Concepts explored:
Model Classes
Navigation
Location
Maps
Table Views
Custom Table View Cells
Drawing App HW - Concepts explored:
  - Procedural Drawing with CoreGraphics
  - Gestures
  - Concert App


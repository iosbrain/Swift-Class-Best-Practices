# Swift Class Best Practices
An Xcode 9 project, written in Swift 4, demonstrating my best practices for designing and coding classes (reference types).

In the [accompanying tutorial](http://iosbrain.com/blog/2018/10/05/some-best-practices-for-designing-and-coding-swift-classes/), I'm going to show you some best practices that will help you design and implement classes (reference types) and then safely leverage reference semantics in Swift. Protocol-oriented programming (POP) and value semantics are all the rage now, but a promising new technology doesn't mean you should throw all your classes away. Why not add some simple constructs to your classes like copy initializers, default initializers, designated initializers, failable initializers, deinitializers, and conformance to the `Equatable` protocol? To get real about my sample code, I'll adopt these constructs in some classes and show you my best practices working in real life for drawing in your iOS app interfaces.

Here's an example of the drawing capabilities of one of the classes I build in the tutorial:

![alt text][logo1]

[logo1]: http://iosbrain.com/wp-content/uploads/2018/10/RedAngleWBlackLine.png "Drawing to screen from Swift class"

-------
Copyright (c) 2018 Andrew L. Jaffee, microIT Infrastructure, LLC, and iosbrain.com.

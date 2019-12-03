# Programming-Languages-Final-Project

## __Why we chose Swift__ 

Mobile apps and games are something that many interact with everyday. In addition, mobile app development sounds like a field worth touching upon given the widespread popularity of these mobile devices. Besides this popularity, mobile app development just sounds like a really fun field to be in, because you get the opportunity to see your code and graphics work hand in hand to produce a highly interactable piece of software, such as a small game, or a food app, etc. Swift is a programming language that has been designed for the development of mobile apps and games for iOS devices, so this is why we decided to pick this as our programming language.

## __A Overview on the History of Swift__

Swift is a very young object oriented programming language that incorporates various ideas from Objective-C, Python, C# and more, with the very first version being announced at the Apple Worldwide Developers Conference in 2014 (1, 2). Actual development of the Swift programming language was started in 2010 by Chris Lattner, with apple programmers joining the following year (1). Prior to swift, Objective-C was used to develop apps for apple devices, but Apple began to have concerns over the low safety level of Objective-C. Objective-C, being extremely close to C, ran the risk that a careless programmer may write a piece of software that accesses the incorrect memory addresses, which could lead to crashes and even security concerns (3). This low level of safety, combined with the increasing hardship of adding in new features that other programming languages were adopting with ease, motivated apple to search for a new programming language, leading them to Swift. Since version 1, swift has undergone major growth, with numerous versions being released. Swift has also been well received by developers around the world, coming in first place for the most loved language in 2015 (4). Swift also became an open source project in 2015, with the aim of advancing the original goals of making a language that is safe, fast, and is expressive (5). In 2016 the first version of Swift as an open source project, Swift 3, was released (5). The most current version of Swift is version 5.1.2, with Swift 5.2 in the works (5).

## __The type of tasks is Swift suitable for and examples of where swift has been used successfully__
Developed by Apple in order to provide developers with a faster, safer, more reliable way to write software, Swift is used in order to create applications for all Apple platforms. This includes iOS, macOS, watchOS, and tvOS. Swift was developed by Apple as a replacement for C-base languages such as C, C++, and Objective-C, meaning it is capable of performing similar tasks. It was however, created in order to be a faster alternative to Objective-C that also benefits from an ease of learning, simpler code, safety, and its interactivity. Because of these reasons, especially its simplicity, it is especially popular among start-up companies and beginning developers. Also, the fact that Swift can serve as both a forward-facing and server side language, it is beneficial to companies because for a product such as Facebook, apps and servers can speak to each other seamlessly (11). Lots of applications currently available for iPhones, iPads, and other iOS devices utilize Swift in their code. Although they are not written entirely in Swift, programs such as Firefox, Wordpress, Airbnb, LinkedIn, Venmo, etc all utilize Swift (10). In addition to iOS app development, the language can also be used on Linux in order to build Swift Libraries.

## __Why should someone consider swift for a particular task__
Swift is a very useful programming language that can be used for anything from systems programming, to mobile and desktop apps, to scaling up and cloud services (5). There are a few important core features that Swift includes that can make it better suited for some tasks than other languages. Originally, Swift was developed by Apple for use with their various operating systems. Thus, if your task is programming in the Apple ecosystem, Swift is a powerful programming language for iOS, iPadOS, watchOS, tvOS, macOS and Linux. Swift is useful when you have a task that requires safety and performance. Swift is implemented with similar core concepts to Objective-C but implements those concepts in a safer way, making it easier to catch software bugs and less likely to have security issues (5). Swift is also 2.6x faster than Objective-C and 8.4x faster than Python (6). Since swift is an expressive, strongly typed language with simplified syntax and grammar, it is easier to read and write. If Swift is considered for a task over Objective-C, the task will be concise and require less code to perform the same functions. For example, the app Lyft originally contained about 75,000 lines of code. Lyft decided to re-write its iOS app using Swift and was able to create the same functionality with less than 25,000 lines of code, 1/3 of the original lines used (7). If you are developing an app that requires decreased memory footprint, Swift may be a good choice. Swift can use dynamic libraries, which stores the libraries outside of your code and only uses them when needed. This is very useful when you are developing in an environment, such as macOS or iOS, where Swift libraries are integrated into every OS release (7).  Thus, your app will take up less space since the libraries can be accessed dynamically within the OS.

## __Interesting features in Swift__
Swift packs a ton of interesting features, however there are some important core features to touch on. Firstly, Automatic Reference Counting (ARC) is a useful feature because it tracks and manages the program’s memory usage, so you don’t need to manage the memory yourself (7). Secondly, Swift offers type safety through introducing an interesting type called Optional. The Optional type safely handles the absence of a value and forces us to handle the nil case explicitly to ensure that no bad assumptions are made about what a variable holds (8). For example, if a variable is an optional String, we know that either the variable is a String or the variable doesn’t have a value (8). Another feature that Swift implements is called a guard statement. A guard is used to transfer program control out of a scope if one or more conditions aren’t met (9). This allows us to return a function early. In that sense, a guard statement can be used like a reverse if statement. However, a guard statement can be more than a reverse if statement. A guard statement can also be used to unwrap Optional bindings using “guard let.” This is useful because it can safely unwrap an Optional variable, which can guarantee it to be of a type, such as String.

### *Optional* type:
An optional in Swift is a type that can hold either a value or no value.  An optional is a kind of container. For example, an optional String is a container which might contain a string. Optionals are written by appending a `?` to any type:
```
var firstname: String?
```
This above example means that the variable firstname can either be a String or does not contain anything, represented by the `?`.

### Guard statement usage:
Guard looks like and if-else statement without the "if" part. However, guard can be used for much more than an if statement because it was designed to transfer program control out of a scope if one or more of the conditions aren't met. For example, guard can be used to early exit when an optional unwrapping fails. 
```
guard condition else {
    statements
}
```
String unwrapping. Str is safely unwrapped and is guaranteed to be a String type from here on:
```
guard let str = strOptional else {
    return
}
```

## __Source Links__

1. http://nondot.org/sabre/
2. https://theswiftdev.com/2017/10/03/evolution-of-the-swift-language/
3. https://arstechnica.com/gadgets/2014/06/a-fast-look-at-swift-apples-new-programming-language/
4. https://insights.stackoverflow.com/survey/2015#tech-super
5. https://swift.org/

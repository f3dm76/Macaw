<img src="https://image.ibb.co/jHXuWK/macaw_cover.png" alt="macaw_cover" border="0">

[![CI Status](https://travis-ci.org/exyte/Macaw.svg?style=flat)](https://travis-ci.org/exyte/Macaw) [![Version](https://img.shields.io/cocoapods/v/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw) [![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-0473B3.svg?style=flat)](https://github.com/Carthage/Carthage) [![License](https://img.shields.io/cocoapods/l/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw) [![Platform](https://img.shields.io/cocoapods/p/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw)

Macaw is an open source programming library that provides API for software developers. It provides primitives, visual effects, and animations for two-dimensional drawing across macOS, iOS, watchOS, and tvOS.  Macaw allows you to convert designs into scalable native views, fitting different screens.

### Key Features

* SVG rendering
* scene serialization and scene deserialization into an SVG or Macaw file
* scene may include multiple responsive objects
* creating shapes in CGGraphicContext in a reasonably easy way
* friendly interface for CAAnimation 
* Macaw carefully handles changes in public API, which insures compiling even of a very old code you'd written with Macaw

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* iOS 8.0+
* Mac OS X 10.11+
* Xcode 7.3+

### Installing

#### [with CocoaPods](http://cocoapods.org)

Add the following line to your Podfile:
```ruby
pod "Macaw", "0.9.1"
```

#### [with Carthage](http://github.com/Carthage/Carthage)

Add the following dependency to the Cartfile

```ogdl
github "Exyte/Macaw" ~> 0.9.1
```
For more details refer to [Getting Started Tutorial] (https://github.com/exyte/Macaw/wiki/Getting-started)

Get started with Macaw in several lines of code:

```swift
class MyView: MacawView {

	required init?(coder aDecoder: NSCoder) {
		let text = Text(text: "Hello, World!", place: .move(dx: 145, dy: 100))
		super.init(node: text, coder: aDecoder)
	}

}
```

<img src="http://i.imgur.com/ffPc4mr.png" width="475">

#### Build from sources
* clone the repo `git@github.com:exyte/Macaw.git`
* open terminal and run `cd <MacawRepo>/Example/`
* run `pod install` to install all dependencies
* run `open Example.xcworkspace/` to open project in the Xcodesage 

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

This project is created and maintained by [exyte](http://www.exyte.com), a ditital agency focused on mobile and VR.
We truly appreciate your feedback and use cases. Please share your story or opinion at info@exyte.com.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

_____________________________________________________________________________________________________



# Macaw [![CI Status](https://travis-ci.org/exyte/Macaw.svg?style=flat)](https://travis-ci.org/exyte/Macaw) [![Version](https://img.shields.io/cocoapods/v/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw) [![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-0473B3.svg?style=flat)](https://github.com/Carthage/Carthage) [![License](https://img.shields.io/cocoapods/l/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw) [![Platform](https://img.shields.io/cocoapods/p/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw)
Macaw is an easy-to-use iOS library for vector graphics and animation. 



<img src="http://i.imgur.com/rQIh3qD.gif" height="280"> <img src="http://i.imgur.com/bIgHtzt.gif" height="280"> <img src="http://i.imgur.com/NiBT2rv.gif" height="280"> <img src="http://i.imgur.com/Un8TJKc.gif" height="280">

## Key Feature

Scalable Vector Graphics rendering *picture+script* 

<img src="https://image.ibb.co/b3wcke/tiger_svg.png" alt="tiger_svg" border="0">

## Features

## Usage

### Requirements

* iOS 8.0+
* Mac OS X 10.11+
* Xcode 7.3+

### Installation

#### [CocoaPods](http://cocoapods.org)

To install it, simply add the following line to your Podfile:
```ruby
pod "Macaw", "0.9.1"
```

#### [Carthage](http://github.com/Carthage/Carthage)

```ogdl
github "Exyte/Macaw" ~> 0.9.1
```
For more details refer to [Getting Started Tutorial] (https://github.com/exyte/Macaw/wiki/Getting-started)

### To build from sources
* clone the repo `git@github.com:exyte/Macaw.git`
* open terminal and run `cd <MacawRepo>/Example/`
* run `pod install` to install all dependencies
* run `open Example.xcworkspace/` to open project in the Xcodesage 

Get started with Macaw in several lines of code:

```swift
class MyView: MacawView {

	required init?(coder aDecoder: NSCoder) {
		let text = Text(text: "Hello, World!", place: .move(dx: 145, dy: 100))
		super.init(node: text, coder: aDecoder)
	}

}
```

<img src="http://i.imgur.com/ffPc4mr.png" width="475">


#### Examples

[Macaw-Examples](https://github.com/exyte/macaw-examples) is a repository where you can find various usages of the `Macaw` library from simple charts to the complex periodic table.

## Resources

#### Docs

* [Getting started guide](https://github.com/exyte/Macaw/wiki/Getting-started)
* [Render SVG file](https://github.com/exyte/Macaw/wiki/Render-SVG-file)
* [Content animation](https://github.com/exyte/Macaw/wiki/Content-animation)
* [Morphing animation](https://github.com/exyte/Macaw/wiki/Morphing-animation)
* [Change Log](https://github.com/exyte/Macaw/wiki/Change-Log)


#### Posts
* [Replicating Apple Design Awarded Applications](https://medium.com/exyte/replicating-apple-design-awarded-applications-70e5df4c4b94#.ckt1hfnei)
* [How friendly can drawing API be on iOS?](https://medium.com/exyte/how-friendly-can-drawing-api-be-on-ios-b3a818bf8105#.o9i35zcai)
* [Macaw iOS Library: Morphing Animations](https://medium.com/exyte/macaw-ios-library-morphing-animations-and-touch-events-a4cb1c0be97f)


## About the developers

This project is maintained by [exyte](http://www.exyte.com). We design and build mobile and VR/AR applications.

### Motivation

Modern designs contain tons of illustrations and complex animations. We had to spend a lot of time on converting designs into native views that will be resizable for different screens until we had enough and created Macaw. It helps to reduce development time to a minimum and describe all graphics in high level [scene](https://en.wikipedia.org/wiki/Scene_graph) elements or even render SVG graphics right from your design tool with Macaw events and animation support.

We truly appreciate your feedback and use cases. Please share your story or opinion at info@exyte.com.

### Areas for Improvements / involvement
* XXX
* XXX

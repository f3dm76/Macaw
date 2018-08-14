<img src="https://image.ibb.co/jHXuWK/macaw_cover.png" alt="macaw_cover" border="0">

[![CI Status](https://travis-ci.org/exyte/Macaw.svg?style=flat)](https://travis-ci.org/exyte/Macaw) [![Version](https://img.shields.io/cocoapods/v/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw) [![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-0473B3.svg?style=flat)](https://github.com/Carthage/Carthage) [![License](https://img.shields.io/cocoapods/l/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw) [![Platform](https://img.shields.io/cocoapods/p/Macaw.svg?style=flat)](http://cocoapods.org/pods/Macaw)

Macaw provides primitives, visual effects, and animations for two-dimensional drawing across macOS, iOS, watchOS, and tvOS.  It allows you to convert designs into scalable native views, fitting different screens. It is also open source (surprise-surprise) and regulary updated.

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
For more details refer to [Getting Started Tutorial](https://github.com/exyte/Macaw/wiki/Getting-started)

Example:

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

### Areas for Improvements / involvement
* XXX
* XXX

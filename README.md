<h1 align="center">
	<img src="https://raw.githubusercontent.com/greenpintab/encryptme/master/Artboard-2.png" alt="logo">
	<br>
</h1>

> Encryption is easy. Key management is not.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/greenpintab/encryptme/blob/master/LICENSE)
[![Swift 5.0](https://img.shields.io/badge/Swift-5.0-blue.svg?style=flat)](https://developer.apple.com/swift/)
[![Pod compatible](https://img.shields.io/badge/Pod-Compatible-blue.svg)](https://github.com/CocoaPods/CocoaPods)

Client-side encryption is vital for privacy, business confidentiality on third party, untrusted clouds.

## Content
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Contribute](#contribute)
- [License](#license)

## Installation

### CocoaPods

[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate encryptme into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod "encryptme", :git => 'https://github.com/user/encryptme.git'
```

## Usage
### Create
```swift
var vault = try Encryptme.create(password: "secret password")
```
### Open
```swift
var vault = try Encryptme.create(password: "secret password")
```
### Done
```swift
var vault = try Encryptme.create(password: "secret password")
```

## Credits
Encryptme is owned and maintained by [Parmezan](http://parmezan.io).

## Contribute
If you believe you have identified a security vulnerability with Encryptme, you should report it as soon as possible via email to security@parmezan.io. Please do not post it to a public issue tracker.

## License
Encryptme is licensed under the MIT License. See the [LICENSE.md](https://github.com/greenpintab/encryptme/blob/master/LICENSE) file for details

![Encryptme - Simple and Secure](https://raw.githubusercontent.com/greenpintab/encryptme/master/Artboard-1.png)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/greenpintab/encryptme/blob/master/LICENSE)
[![Swift 5.0](https://img.shields.io/badge/Swift-5.0-blue.svg?style=flat)](https://developer.apple.com/swift/)
[![Pod compatible](https://img.shields.io/badge/Pod-Compatible-blue.svg)](https://github.com/CocoaPods/CocoaPods)

> Encryption is easy. Key management is not.

Client-side encryption is vital for privacy, business confidentiality on third party, untrusted clouds.

# Content
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Migration Guides](#migration-guides)
- [Communication](#communication)
- [Installation](#installation)

## Installation

### CocoaPods

[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate encryptme into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod "encryptme", :git => 'https://github.com/user/encryptme.git'
```

## Usage
### Create
```swift
var vault = try Vault.create(password: "secret password")
```
### Open
```swift
var vault = try Vault.create(password: "secret password")
```
### Close
```swift
var vault = try Vault.create(password: "secret password")
```

## License
Encryptme is licensed under the MIT License. See the [LICENSE.md](https://github.com/greenpintab/encryptme/blob/master/LICENSE) file for details

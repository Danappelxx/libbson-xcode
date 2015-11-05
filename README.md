# libbson-xcode
This repository is a mirror of the [MongoDB libbson](https://github.com/mongodb/libbson) library, except the source files are place in an Xcode project. This is done to allow libbson to build through Carthage.

Compatible with [libmongoc-xcode](https://github.com/Danappelxx/libmongoc-xcode).

# Usage
Add the following line to your Cartfile:
```carthage
github "Danappelxx/libbson-xcode" "master"
```
and run 
```shell
$ carthage bootstrap
```
in your source file, simply
```swift
import bson
```
and enjoy!

# Documentation
Documentation is available [here](http://api.mongodb.org/libbson/current/).

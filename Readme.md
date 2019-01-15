# Conan protobuf-cpp

This repository contains the conan receipe that is used to build the protobufcpp packages at appcom.

For Infos about the library please visit the [google](https://developers.google.com/protocol-buffers/) page.
The license of the library can be found on [github](https://github.com/protocolbuffers/protobuf/blob/master/LICENSE).
This repository is licensed under the [MIT License](LICENSE).

## macOS

To create a package for macOS you can run the conan command like this:

`conan create . protobufcpp/3.6.1@appcom/stable -s os=Macos -s os.version=10.14 -s arch=x86_64 -s build_type=Release -o shared=False`

### Requirements

* [CMake](https://cmake.org/)
* [Conan](https://conan.io/)
* [Xcode](https://developer.apple.com/xcode/)

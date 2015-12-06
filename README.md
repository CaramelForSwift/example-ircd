This project is a sample app showing how to build an IRC server in [Caramel for Swift](https://github.com/CaramelForSwift/Caramel.git).

This project is in active development and should not be used as a guide to best practices for writing in Caramel.

# Install

First you need to build libuv as per the directions in the [CUv](https://github.com/CaramelForSwift/CUv) repository. Then this should be runnable via `swift build`.

Currently there is an issue with building where the code reports the following error:

`undefined reference to `_swift_FORCE_LOAD_$_swiftGlibc'`

# License (MIT) 

Copyright (c) 2015 Steve Streza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

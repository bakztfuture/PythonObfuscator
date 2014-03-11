Simon's Python Obfuscator
=========================

Try the obfuscator directly at: http://pyobf.herokuapp.com

This open source obfuscator hopes to obfuscate python scripts and make the scripts unreadable / hard to decipher, since you can somehow retrieve the source code from de-compiling the Python bytecode.

Obfuscation process inspired by one of the most famous Javascript obfuscator, /packer/
http://dean.edwards.name/packer/

Changelog
=========

v0.3: Used base64 to fix the backslash issues! (Thanks @jihop for the idea) Should be able to obfuscate any code, including already obfuscated code, and even obfuscator itself.

v0.2: changed the pack structure, still trying to fix the back slash problem.

v0.1: Basic hack, lots of bugs, cannot even obfuscate itself, or obfuscated code.

Author: Simon Liang
2013

License
=======

The MIT License (MIT)

Copyright (c) 2014 Haoran Liang

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
# ruby-build for OpenBSD

ruby-build provides a simple way to compile and install Ruby on OpenBSD

### OpenBSD Package Prerequisites

* bash
* libyaml
* libffi
* [rbenv](https://github.com/sstephenson/rbenv)

### Supported OpenBSD Versions

* 5.0 i386/amd64
* 5.1 i386/amd64

### Installing ruby-build

    $ mkdir -p ~/.rbenv/plugins
    $ cd ~/.rbenv/plugins
    $ git clone git://github.com/mbkulik/ruby-build.git

### Installing Ruby

You can use it with [rbenv](https://github.com/sstephenson/rbenv):

    $ ruby-build 1.9.2 ~/.rbenv/versions/1.9.2

ruby-build provides an `rbenv-install` command that shortens this to:

    $ rbenv install 1.9.2

### Supported Ruby Versions

* 1.8.7-p370
* 1.9.2-p320
* 1.9.3-p194

### Version History

### 20120712

* Ruby 1.8.7 updated to p370

#### 20120519

* Initial Support for OpenBSD

### License

(The MIT License)

Copyright (c) 2011 Sam Stephenson

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

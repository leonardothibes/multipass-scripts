Multipass
=========

Script for instalation of development scenarios into [Multipass](https://multipass.run/).

Multipass Instalation
=====================

#### Enabling Snap, if necessary
```bash
rm -f /etc/apt/preferences.d/nosnap.pref
sudo apt update
sudo apt install snapd
```

#### Instaling Multipass
```bash
sudo snap install multipass
```

Scenarios Instalation
=====================

**Node.js**
```bash
wget -qO- https://raw.githubusercontent.com/leonardothibes/multipass/master/scenarios/node.sh | bash
```

**PHP 7.4**
```bash
wget -qO- https://raw.githubusercontent.com/leonardothibes/multipass/master/scenarios/php-7.4.sh | bash
```

**Basic Bash**
```bash
wget -qO- https://raw.githubusercontent.com/leonardothibes/multipass/master/scenarios/bash.sh | bash
```

Author
------

 * **Leonardo Thibes <leonardothibes@gmail.com>**

LICENSE
=======

Copyright (c) 2023 Leonardo Thibes

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

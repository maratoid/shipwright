# ShipWright

A tool for quickly creating a ship-in-a-bottle cloud:

* chef data bags
* chef recipes
* zerg task
* list of gerrit reviews

## Usage

* Make sure you are setup for MTN gerrit access with all the correct keys and permissions. 
* Make sure that your gerrit username is in your global gitconfig.
* Obtain a validator key from someone on the Platform Services team. 

```
git clone git@github.com:MTNSatelliteComm/shipwright.git
cd shipwright
rake install
shipwright wizard
```

to cleanup a changeset/ip from previous run - must not have been merged yet:

```
shipwright clean
```

## Licence

Copyright 2014 by MTN Sattelite Communications

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to
deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
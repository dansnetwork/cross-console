# Cross-Console script
Sometimes you just need to control the console.

# Install

## Via bower
```
bower install cross-console
```

## Download Manually

* Download the files using the GitHub .zip download option
* Use either the compressed `bin/cross-console.min.js` or the `lib/cross-console.js` file.


# Features
 - attempts to implements console in all environments
 - allows environment differences. While in 'production' console is disabled. This keeps errant `window.console` from breaking a page or showing up to a user.
 - creates the ability to send console.error to another Function while in production (for easier error management like sending an email)

# Coming soon
 - I haven't fully tested the ability to use this in Node due to the conflicts that may occur with `console`. I'll update the repository and add to NPM when that has been sorted out
 
# License
The MIT License (MIT)

Copyright (c) 2013 Drew@geedew.com 

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
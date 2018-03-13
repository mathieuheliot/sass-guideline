# sass-guideline
SASS Guide: A starting point for Frontend development teams to provide consistency through good practices.

## Naming conventions
### Variables
Use consistent names for all variables following a pattern that describes the variable's feature then its type.

My recommanded pattern is `$[name]-[scope?]-[variant?]-[type]`.

```scss
// Primary colors
// @type Color
$primary-color: rgb('255, 121, 0');
$primary-background-color: rgb('255, 255, 255');
$primary-link-color: rgb('255, 121, 0');

// Secondary Colors
// @type Color
$secondary-color: rgb('80, 190, 135');
$secondary-text-color: rgb('221, 221, 221');
$secondary-text-darken-color: rgb('153, 153, 153');
```

_Why?: Naming conventions help provide a consistent way to find content at a glance. Consistency within the project is vital. Consistency with a team is important. Consistency across a company provides tremendous efficiency._

_Why?: The naming conventions should simply help you find your code faster and make it easier to understand._

License
--------------

The MIT License (MIT)

Copyright (c) 2014 Arshad Chummun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

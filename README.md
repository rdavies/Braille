Braille
=======

UIView extension for finding accessibility elements.

Within a view hierarchy, views can be retrieved based on their accessibility properties.

For example, in order to find an accessibility element labelled 'Add' (the default label for an Add button in a navigation bar), the following code example would suffice:

    NSArray *elements = [[self view] viewsWithAccessibilityLabel:@"Add"];
    UIView *addButton = [elements objectAtIndex:0];

See UIView+BRLAccessibility.h for the full list of methods.

Installation
============

Braille can be installed with [CocoaPods](https://github.com/CocoaPods/CocoaPods) by adding `pod 'Braille', '~> 0.1.0'` to your Podfile.

License
=======

    Copyright (c) 2013 Ryan Davies
    
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

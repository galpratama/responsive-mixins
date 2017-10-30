# Responsive Mixin 

Responsive Mixin to make your life easier and change your life forever. (not really)

## Available mixin to use
- Bootstrap (`xs, sm, md, lg`)
- Non-Retina Display (`non-retina`)
- Retina Display (`retina, retina-3x, retina-4x`)
- iPhone 5/5S/SE (`iphone-5, iphone-5-portrait, iphone-5-landscape`)
- iPhone 2G, 3G, 4, 4S (`iphone-4, iphone-4-portrait, iphone-4-landscape`)
- iPad All generations - including iPad mini (`ipad, ipad-portrait, ipad-landscape`)
- Custom breakpoints (in px)

## How to use

Check `usage.scss`, or, if you're too lazy, check below :

```scss
.your-element {
   height:5em; 
   @include respondto (xs, sm, md) {
      height: 2em;
   }
   @include respondto (md, retina) {
      color: #fff;
   }
   // custom breakpoint
   @include respondto (120, non-retina) {
      color: red;
   }
}

```

## Modification License

```
Copyright (c) 2017 Galih Pratama

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

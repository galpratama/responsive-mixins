# Responsive Mixin 

Responsive Mixin to make your life easier and change your life forever. (not really)

## Available mixin to use
- Bootstrap (`xs, sm, md, lg`)
- Non-Retina Display (`non-retina`)
- Retina Display (`retina, retina-3x, retina-4x`)
- iPhone 5/5S/SE (`iphone-5, iphone-5-portrait, iphone-5-landscape`)
- iPhone 2G, 3G, 4, 4S (`iphone-4, iphone-4-portrait, iphone-4-landscape`)
- iPad All generations - including iPad mini (`ipad, ipad-portrait, ipad-landscape`)

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

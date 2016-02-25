# Bootstrap 3 Responsive Mixin 

Bootstrap 3 Responsive Mixin to make your life easier and change your life forever.

Forked from Flo, Peschee and AmoHoban from Github Gists

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

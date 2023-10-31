# CSS Responsive Queries

Media query is a CSS technique introduced in CSS3.

It uses the @media rule to include a block of CSS properties only if a certain condition is true.

```css
 @media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
```

We try to develop the mobile view first. This will make the page display faster on smaller devices.

### Device breakpoint

```css
 /* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {style here}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {...}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {...}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {...}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {...} 
```

### Responsive in terms of orientation 

Media queries can also be used to change layout of a page depending on the orientation of the browser.
```css
@media only screen and (orientation: landscape) {
  body {
    background-color: lightblue;
  }
}
```


## References

[Responsive design][def]

[def]: https://www.w3schools.com/css/css_rwd_mediaqueries.asp
# Position :- Relative or Absolute

### Relative Positioning
An element with position: relative; is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

```css
 div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}
```

### Absolute Position
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

```CSS
 div.absolute {
  position: absolute;
  left: 30px;
  top: -20px;
  border: 3px solid #73AD21;
}
```
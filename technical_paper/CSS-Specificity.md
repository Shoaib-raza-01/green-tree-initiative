# CSS Specificity

CSS specificity is a fundamental concept that determines which styles should be applied to an HTML element when conflicting or competing styles are defined. Specificity helps the browser decide which CSS rule takes precedence and is applied to an element. Specificity is crucial in resolving style conflicts and achieving the desired layout and appearance for web pages.

* **Inline Styles:** Styles defined directly on an HTML element using the style attribute have the highest specificity. They are applied with the highest priority.

* **ID Selectors:** Styles defined with an ID selector (e.g., #myElement) have a high specificity. An ID selector is unique on a page and applies to a single element.

* **Class Selectors and Attribute Selectors:** Styles defined with class selectors (e.g., .myClass) or attribute selectors (e.g., [data-attribute]) have moderate specificity. Class selectors can be used on multiple elements, while attribute selectors target elements with specific attributes.

* **Type Selectors:** Styles defined with element or type selectors (e.g., p, div, a) have the lowest specificity. They target all elements of a given type.

* **Universal Selectors and Combinators:** Styles defined with universal selectors (*) and combinators (e.g., +, ~, >, etc.) typically have low specificity.

```html
<p id = 'myStyle' class = 'myClass'> this is a para</p>
```

```css
#myStle {
  color: red; 
}

p.myClass {
  color: blue; 
}

p {
  color: green; 
}
```

It will have a red text color because the rule with the ID selector has the highest specificity.



## References
[css specificity](https://www.w3schools.com/css/css_specificity.asp)
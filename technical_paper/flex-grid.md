# Flex and Grid

Flex and Grid are two display types which help us to achieve some really complex designs and columns which are responsive in nature

## Flexbox

Flexbox aligns all the contents in a horizontal direction by default but we can change the it by using a property `flex-direction`

**Properties of FLEXBOX**

1. **flex-direction  :**
The column value stacks the flex items vertically (from top to bottom)
```css
.flex-container {
  display: flex;
  flex-direction: column;
}
```
2. **flex-wrap :**
This property controls whether or not the flex container is single line or multi-line, it also allows you to specify where to wrap the lines.
```css
.flex-container {
  display: flex;
  flex-wrap: wrap;
}
```
3. **flex-flow :**
This property is shorthand for setting both the flex-direction and flex-wrap properties in a single declaration.
```css
.flex-container {
  display: flex;
  flex-flow: row wrap;
}
```
4. **justify-content: **
The center value aligns the flex items at the center of the container
```css
.flex-container {
  display: flex;
  justify-content: center;
  /* justify-content: flex-end;
  justify-content: flex-start;
  justify-content: space-between; */
}
```
5. **align-items :**
The center value aligns the flex items at the center of the container
```css
.flex-container {
  display: flex;
  height: 200px;
  align-items: center;
}
```
6. **align-content :**
The align-content property is used to align the flex lines.
The stretch value stretches the lines so they take up the full height of the container
```css
 .flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: stretch;
}
```

## Grid
Grid offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

1. **grid-template-columns**
The grid-template-columns property defines the number of columns in your grid layout, and it can define the width of each column. The value is a space-separated-list, where each value defines the width of the respective column.
```css
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto;
}
```
Next we can define the area where a specific content will go using `grid-template-areas` property

```css
.grid-example{
    display: grid;
    grid-template-areas : "a b"
    "c c";
}
.menu{
    grid-area: c;
    display:flex
}
.button{
    grid-area: b;
}
.logo{
    grid-area: a;
}
```


## References

* [FLEXBOX][def]

[def]: https://www.w3schools.com/css/css3_flexbox_container.asp#flex-direction

* [GRID][def2]

[def2]: https://www.w3schools.com/css/css_grid_container.asp
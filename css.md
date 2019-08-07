###CSS Cascading Style Sheets 

###Cascading 
elemnets < class < ids < inline styles 
```
div {
    display: auto;
}

class{
display: none;
}

#id {
    display block;
}

<div style = {{display: 'flex'}} />
```
### units 
- `px`: pixel units 
- `rem`: ratio against the font-size  of the `html` element 
- `%`: percentage units 
- `vh` / `vw` : veiw height/ veiw width . Useful for making sections with specific aspects ratios.
- ` calc (100% - 50px)` : calculates. must have spaces before and after operator

###layouts / flexbox 

- `display: flex;`
- `flex - direction`
    - `row` (default) 
    - ` column ` 
    - `row-reverse`
    - `column-reverse`
- `flex- shrink: 0; ` will stop a f/lexbox child from shrinking 
- ` align-items`: aligns on the axis perpendicular to you layout
    - `center`
    -`flex-start`
    -`flex-end`
    -`space-between`
    -`space-around`
-`justify- content` : aligns on the axis of the layout( same values as "align-items" )
- **note**: flexbox will resize your items. You can use `min-width`/`max-width` to limit how much flexbox will resize.

### elements 
-`margin` : space outside an element 
    - `1px 2px 3px 4px` : top, right, bottom, left 
    - `0 auto`: will center an element 
- `padding`: space inside 
- `width/height`
- `font-size`
- `min-width/max-width/min-height/max-height`
- `line-height`: vertical spacing of text 
- `border 1px solid black;`
- `border-radius`: rounded corners 
- `box-shadow` 
- `position`
    - `relative`: positioned in relation to the elemnts aaround it 
    - `absolute`: positioned in relation to its closest parent that has a "relative"  position.
    - `fixed`: positioned in relation to the `body`  then you can use `top`, `left`, `right`, `bottom` 
    - also allows `z-index`

### colors 
-`colors`: font color 
-`background`: actual background color 
    - names like `green`, `red` etc.
    - `rgb(0,0, 255)` or `rgba(0,0,255, 0.5)` for opacity 
    - hex: `#00FF00` = `rbg(0,255,0)`

### media queries 
```
@media only screen and (min-width: 600px){
/* these styles will only appl if screen is > 600px */
}

```

### element states psedo elements
-`.class: hover {}`
-`.class: focus`
```
.class: after{
content: "";
}
```

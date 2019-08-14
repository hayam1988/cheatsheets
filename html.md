#html 

### basic elements

`<div>`: basic wrapper element.(default = display: block;)

`span`: (default = display: inline-block). Usually used for text 

`<p>`: paragraph. Has built in margins 

`<h1>`...`<h5>`: headers. built-in font-sizes 

`<a>`: links! (anchor)
- href=" https://something.com" 
- target="_blank" to open a new tab 

`<img>`: images 
- src="/url_of_your_image"
- alt="name of your image" for accessibility 


### semantic tag
- `<header>`
- `<main>`
- `<footer>`
- `<nav>`
- `<pre>`: preformated text 
- `<code>`: code snippets 
- `<aside>`
- `<article>`


###forms 
`<form>`: has an "onSubmit" prop

All forms inputs have "value" and "onChange" props 
- `<input>`: text input 
- `<button>`: (if type="submit" then clicking the button will submit the surround from)
- `<select>`: drop down (has `<option>` elemnets in it)
- `<radio>`
- `<chekbox>`: (has a "checked" prop instead of "value" )


### built in props
- style={{height: 40;}}
- className (to add a CSS class)
- id ( add in CSS)
- onClick (all elements are clickable)
- onHover


### React notes 
- all props are camelCase! like className, onClick, onChange... in original HTML they are all lowercase 

- in original HTML, props MUST be strings 

- in original HTML , "className" is just "class" 








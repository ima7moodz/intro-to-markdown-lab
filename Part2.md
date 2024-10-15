# The anatomy of CSS selector

## CSS selector 5 categories:-

1. Simple selectors
   > select elements based on name, id, class
2. Combinator selector
   > select elements based on a specific relationship between them
   > **_Example_**

`````CSS
div > p {
background-color: yellow;}
3. Pseudo-class selectors
>select elements based on a certain state
***Example***
````CSS
a:hover {
color: #000;}
4. Pseudo-elements selectors
>select and style a part of an element
***Example***
````CSS
p::first-letter {
color: #ff0000;
font-size: xx-large;}
5. Attribute selectors
>select elements based on an attribute or attribute value
***Example***
````CSS
a[target] {
background-color: yellow;}

For more information you can visit this link
[W3school](https://www.w3schools.com/CSS/css_selectors.asp#:~:text=CSS%20selectors%20are%20used%20to%20%22find%22%20%28or%20select%29,selectors%20%28select%20elements%20based%20on%20a%20certain%20state%29)
`````

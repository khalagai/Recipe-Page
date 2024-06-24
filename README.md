# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

My major learning was how to color the numbers in an ordered list separately.

code snippets, see below:

```css
ol {
    margin:0 0 1.5em;
    padding:0;
    counter-reset:item;
  }
   
  ol>li {
    margin: 0;
    padding:0 0 1 2em;
    text-indent:-2em;
    list-style-type:none;
    counter-increment:item;
  }
   
  ol>li:before {
    display:inline-block;
    width:1.5em;
    padding-right:0.5em;
    font-weight:bold;
    color: hsl(332, 51%, 32%);
    text-align:right;
    content:counter(item) ".";
  }
```
development.**

### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - This helped me with the code above. I need to practice more on that.

## Acknowledgments

- dcodesmith - From Stack Overflow.
#   R e c i p e - P a g e  
 
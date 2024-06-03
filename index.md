# CSS - Key Points

- **CSS** - Cascading Style Sheet
- CSS is not a programming language; it is style for content of a webpage.
- Row are building block of CSS
- h1 {
     color: black;
   }
- `h1` - selector, `color` - property, `blue` - value
- If same classname having different styles, it will take `lowest` classname style
- If one selector having classes then it takes that style.
- Classname is more specific than tags, class style override tag's style
- Id is more specific than classname, will represent like #idname {}
- !important is override Id, important use is not a good practice

## Pseudo class
- Representation is :
- <ol>
     <li classname="example">
         zero 
     </li>
     <li classname="example">
          one
     </li>
</ol>
- .example:first-child{
      color: red;
      }
-:focus,:active,: visited, :link are examples


###Pseudo Elements
- :: - Repesentation
- ::after, ::before -examples

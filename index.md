# CSS - Key Points

- **CSS** - Cascading Style Sheet
- CSS is not a programming language; it is style for content of a webpage.
- Rules are the building blocks of CSS
- Example of a CSS rule:
  ```css
  h1 {
    color: black;
  }

- `h1` - selector, `color` - property, `blue` - value
- If the same class name has different styles, it will take the last defined class name style.
- If one selector has multiple classes, it takes that style.
- Class name is more specific than tags; class style overrides tag's style.
- ID is more specific than class name and is represented like `#idname {}`.
- `!important` overrides ID, but using `!important` is not good practice.
  
## Pseudo class
- Representation is :
  ```html
  <ol>
      <li class="example">
          zero 
      </li>
      <li class="example">
          one
      </li>
  </ol>
- Example of a pseudo-class:
  ```css
  .example:first-child {
      color: red;
  }
- :focus,:active,: visited, :link are examples


### Pseudo Elements
- :: - Repesentation
- ::after, ::before -examples

#### Box-Model or Layout

- **Display Types**
- Block and Inline Block
- Flex and Inline Flex
- Grid and Inline Grid

  
- Margin is space outside of element between it and other elements
- Inside border is padding, spacing inside the element
- ```Flex
  display: flex;
  justify-content: flex-end,center, space-between, space-around
  flex-direction: column, row;

  display: grid;
  grid-template-column: 1fr 1fr;
  row-gap: 10px;
  column-gap: 20px;

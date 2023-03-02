# SIMPLE CSS

An almost class-less stylesheet for quick results with minimal effort Most HTML elements will be styled effectively out of the box, including main heading, navigation, sections/articles/divs, lists, tables, forms, etc.

Steve Copley, Waimea College


## Some extras:
- A large 'hero' style panel is supported via class="hero"
- Responsive section/article/div columns are supported via class="columns"
- Full-width section/article/div are supported via class="full-width"
- Blocks can be styled as 'cards' via class="card"
- Links can be styled as buttons via class="button"
- Buttons/text/cards can be highlighted via class="success/warning/error/accent"
- Required form fields are marked automatically if empty
- Responsive navigation menu, either within header, or outside is supported
- Responsive mobile-style navigation menu is suppoorted via a checkbox toggle:

```html
<header>
    <h1>Main Heading</h1>

    <nav>
        <label for="toggle">Open</label>
        <input id="toggle" type="checkbox">

        <ul>
            <label for="toggle">Close</label>

            <li><a href="#">Link</a></li>
            <li><a href="#">Link</a></li>
            ...
        </ul>
    </nav>
</header>
```

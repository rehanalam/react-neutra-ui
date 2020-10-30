## NEUTRA - ReactJs Tool kit
The NEUTRA Design System is a series of individual styles and components, that when combined make beautiful, intuitive designs. These designs are systemic and logical, as they all follow the same universal principles.

The Neutra Design System is comprised of:
- Neutra Style Guide
- Neutra component library, which contains ReactJs reuseable components.

### Install
Install package using npm
```markdown
npm install react-neutra-ui
````

### Import
Import React components from the appropriate package.
```markdown
import { Button } from "@react-neutra-ui";
...
<Button fill="primary" text="button content" onClick={incrementCounter} />
 ```
```markdown

Syntax highlighted code block
````

# Button

```mardown
<Button text="Add Manually"
        fill="primary"
        onClick={() => { }}/>
```

Following are the HTML props which will pass down to child button element.
```markdown
| Props | Description  |
|--|--|
| `id` | *optional* - **`string`** <br> ID to pass along to a child element |
| `className` | *optional* - **`string`** <br> A space-delimited list of class names to pass along to a child element. |
| `text` | *optional* - **`string`** <br> Action button text |
| `fill` | **`transparent`** \| **`default`** \| **`primary`** \| **`secondary`** \| **`tertiary`** \| **`danger`** \| **`link`** <br>  Color variants of button |
| `onClick` | *optional* - **`React.MouseEvent<HTMLButtonElement>`** <br> Click event handler.|
| `style` | *optional* - **`React.CSSProperties`** <br> Inline CSS styles |
| `icon` | *optional* - **`ReactNode`** <br> Icon element which renders before button text |
| `type` | *optional* -  **`submit`** **`reset`** **`button`** <br> HTML `type` attribute of button |
```

## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rehanalam/react-neutra-ui/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

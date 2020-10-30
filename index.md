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

```markdown
<Button text="Add Manually"
        fill="primary"
        onClick={() => { }}/>
 ```

Following are the HTML props which will pass down to child button element.

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

# Form Controls

## Toggle Switch

```markdown
<ToggleSwitch label="Switch"
			  checked={true}
			  onChange={(e) =>  alert(`Toggle Status: ${{e.target.checked}}`)}/>
 ```

| Props | Description  |
|--|--|
| `label` | *optional* - **`string`** <br> Toggle switch label |
| `checked` | **`boolean`** <br> Checked value checkbox  |
| `onClick` | *optional* - **`ChangeEvent<HTMLInputElement>`** <br> Event handler invoked when input value is changed.|
| `id` | *optional* - **`string`** <br> ID to pass along to a child element |
| `className` | *optional* - **`string`** <br> A space-delimited list of class names to pass along to a child element. |
| `style` | *optional* - **`React.CSSProperties`** <br> Inline CSS styles |
| `disabled` | *optional* - **`boolean`** <br> Disables input when value is true |



## Radio Button
```markdown
<RadioButton id="radio-btn-soup"
	     label="soup"
	     name="meal_choices"
	     value="1"
	     onChange={onChange}/>
```

| Props | Description  |
|--|--|
| `label` | *optional* - **`string`** <br> Toggle switch label |
| `checked` | *optional* - **`boolean`** <br> It indicates whether or not this radio button is the currently-selected item in the group. |
| `value` | **`string`** <br> The string to use as the value of the radio when submitting the form, if the radio is currently toggled on. |
| `name` | **`string`** <br> Name of the group, used to link radio buttons together in HTML.  |
| `onClick` | *optional* - **`React.ChangeEvent<HTMLInputElement>`** <br> Event handler invoked when input value is changed.|
| `id` | *optional* - **`string`** <br> ID to pass along to a child element |
| `className` | *optional* - **`string`** <br> A space-delimited list of class names to pass along to a child element. |
| `style` | *optional* - **`React.CSSProperties`** <br> Inline CSS styles |
| `disabled` | *optional* - **`boolean`** <br> Disables input when value is true |
| `defaultChecked` | *optional* - **`boolean`** <br> use in ReactJs to set default value of radion buton group |



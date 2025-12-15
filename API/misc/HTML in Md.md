|**HTML Tag**|**Purpose (When to Use in Markdown)**|**Example**|**Markdown/HTML Result**|
|---|---|---|---|
|**`<span>`**|Applying inline styling (e.g., color) that isn't supported by standard Markdown.|`<span style="color: blue;">blue text</span>`|blue text|
|**`<div>`**|Creating a block container to group elements and apply block-level styling (e.g., specific padding/margins).|`<div style="border: 1px solid black;">This is a box.</div>`|(A block of content inside a visible border)|
|**`<br>`**|For an explicit, single line break (often used for poetry or addresses where Markdown's double-space break is tricky).|`Line 1<br>Line 2`|Line 1<br><br>  <br><br>Line 2|
|**`<center>`**|To center a block of content (deprecated, but still commonly seen). **Note:** CSS is the preferred method for modern centering.|`<center>Centered Heading</center>`|(Text centered on the page)|
|**`<kbd>`**|To indicate user input, usually from a keyboard.|Press `<kbd>Ctrl</kbd> + <kbd>C</kbd>` to copy.|Press $\text{Ctrl} + \text{C}$ to copy.|
|**`<u>`**|To **underline** text. Markdown has no native underline syntax. **Note:** Use sparingly, as it can be confused with hyperlinks.|This is an `<u>`underlined`</u>` word.|This is an $\text{underlined}$ word.|
|**`<s>`** or **`<del>`**|To indicate text that is struck **through** or deleted. Markdown uses double tilde (`~~`) for this, but the HTML tags are also valid.|`<s>Old Price</s> $10`|$\text{Old Price } \$10$|
|**`<sup>`** or **`<sub>`**|For **superscript** or **subscript** text. Markdown does not have native syntax for these.|E = mc`<sup>2</sup>`<br><br>  <br><br>H`<sub>2</sub>`O|E = mc$^{2}$<br>H$_{2}$O|
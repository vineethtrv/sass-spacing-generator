# Sass Spacing Generator
This will help you to generate several spacing classes for margin and padding.

Eg: `'mt-0'` , `'pl-5'`
  
### The first letter represents the spacing type ( Margin/Padding ).
**m** :  margin 
**p** :  padding 

### The second letter represents the direction.
**l**	: left
**r**	: right
**t** 	: top
**b** 	: bottom
**v**	: vertical (top and bottom)
**h**	: horizontal (left and right)
**a**	: all

### The third represents the spacing value (which you can give your own)
For eg: `mb-0`  means margin-bottom: 0;

### Model
This will be the generated spacing class styling examples 
| class | css |
|--|--|
| .ma-0 | `.ma-0 { margin: 0 }`  |
| .mt-0 | `.mt-0 { margin-top: 0 }`  |
| .ml-0 | `.ml-0 { margin-left: 0 }` | 
| .mh-0 | `.mh-0 { margin-left: 0; margin-right: 0 }` |
| .mv-0 | `.mv-0 { margin-top: 0; margin-bottom: 0 }` |
| .pa-5 | `.pa-5 { padding: 5px }`  |
| .pb-5 | `.pt-5 { padding-bottom: 5px }`  |
| .pr-5 | `.pl-5 { padding-right: 5px }` | 
| .ph-5 | `.ph-5 { padding-left: 5px; padding-right: 5px }` |
| .pv-5 | `.pv-5 { padding-top: 5px; padding-bottom: 5px }` |

### Modify Spacing values
you can create your own spacing classes by modify the **`$spacing`** variable

> `$spacing: 0, 5, 10, 15, 20;`

### Modify Spacing unit
By modifying the **`$unit`** variable you can specify your unit eg: `em, pt, %.`

> `$unit: px;`

 

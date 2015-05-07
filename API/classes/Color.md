
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Color` Class


Defined in: [utils/api/core/color.js:6](../files/utils/api/core/color.js.js)

Module: [Fire](../modules/Fire.md)




Representation of RGBA colors.

Each color component is a floating point value with a range from 0 to 1.

You can also use the convenience method <% crosslink Fire.color Fire.color %> to create a new Color.

### Index

##### Properties

  - `black`
  - `blue`
  - `cyan`
  - `gray`
  - `green`
  - `magenta`
  - `red`
  - `transparent`
  - `white`
  - `yellow`



##### Methods

  - `Color` **constructor**
  - `clamp`
  - `clone`
  - `color`
  - `equals`
  - `fromHEX`
  - `fromHSV`
  - `lerp`
  - `toCSS`
  - `toHEX`
  - `toHSV`
  - `toRGBValue`
  - `toString`





### Details


#### Properties



##### property: `black`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:36` |




##### property: `blue`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:66` |




##### property: `cyan`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:78` |




##### property: `gray`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:48` |




##### property: `green`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:60` |




##### property: `magenta`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:84` |




##### property: `red`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:54` |




##### property: `transparent`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:42` |




##### property: `white`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:30` |




##### property: `yellow`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/core/color.js:72` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Color()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:6` |

###### Parameters
- r <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> red component of the color
- g <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> green component of the color
- b <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> blue component of the color
- a <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> alpha component of the color


##### method: `clamp()`

Clamp this color to make all components between 0 to 1.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:181` |



##### method: `clone()`

Clone a new color from the current color.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:100` |
| Return 		 | <a href="../classes/Color.html" class="crosslink">Color</a> 



##### method: `color()`

The convenience method to create a new <% crosslink Fire.Color Color %>

| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:275` |
| Return 		 | <a href="../classes/Color.html" class="crosslink">Color</a> 

###### Parameters
- r <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- g <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- b <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- a <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `equals()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:109` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- other <a href="../classes/Color.html" class="crosslink">Color</a>  


##### method: `fromHEX()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:192` |
| Return 		 | <a href="../classes/Color.html" class="crosslink">Color</a> 

###### Parameters
- hexString <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `fromHSV()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:246` |
| Return 		 | <a href="../classes/Color.html" class="crosslink">Color</a> 

###### Parameters
- h <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- s <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- v <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `lerp()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:122` |
| Return 		 | <a href="../classes/Color.html" class="crosslink">Color</a> 

###### Parameters
- to <a href="../classes/Color.html" class="crosslink">Color</a>  
- ratio <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> the interpolation coefficient
- out <a href="../classes/Color.html" class="crosslink">Color</a> optional, the receiving vector


##### method: `toCSS()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:155` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 

###### Parameters
- opt <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> "rgba", "rgb", "#rgb" or "#rrggbb"


##### method: `toHEX()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:206` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 

###### Parameters
- fmt <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> "#rgb" or "#rrggbb"


##### method: `toHSV()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:262` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 



##### method: `toRGBValue()`

Convert to 24bit rgb value

| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:235` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 



##### method: `toString()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/color.js:142` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 





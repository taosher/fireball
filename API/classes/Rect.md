
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Rect` Class


Defined in: [utils/api/core/rect.js:5](../files/utils/api/core/rect.js.js)

Module: [Fire](../modules/Fire.md)




A 2D rectangle defined by x, y position and width, height.

see {% crosslink Fire.rect Fire.rect %}

### Index

##### Properties

  - `center`
  - `size`
  - `xMax`
  - `xMin`
  - `yMax`
  - `yMin`



##### Methods

  - `Rect` **constructor**
  - `clone`
  - `contain`
  - `contains`
  - `containsRect`
  - `equals`
  - `fromMinMax`
  - `fromVec2`
  - `intersects`
  - `lerp`
  - `rect`
  - `toString`





### Details


#### Properties



##### property: `center`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/rect.js:174` |




##### property: `size`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/core/rect.js:189` |




##### property: `xMax`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/rect.js:156` |




##### property: `xMin`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/rect.js:132` |




##### property: `yMax`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/rect.js:165` |




##### property: `yMin`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/rect.js:144` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Rect()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:5` |

###### Parameters
- x <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- y <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- w <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- h <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `clone()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:82` |
| Return 		 | <a href="../classes/Rect.html" class="crosslink">Rect</a> 



##### method: `contain()`

Checks if rect contains

| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:54` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 

###### Parameters
- a <a href="../classes/Rect.html" class="crosslink">Rect</a> Rect a
- b <a href="../classes/Rect.html" class="crosslink">Rect</a> Rect b


##### method: `contains()`

Returns true if the point inside this rectangle.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:212` |

###### Parameters
- point <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `containsRect()`

Returns true if the other rect totally inside this rectangle.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:229` |

###### Parameters
- rect <a href="../classes/Rect.html" class="crosslink">Rect</a>  


##### method: `equals()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:90` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- other <a href="../classes/Rect.html" class="crosslink">Rect</a>  


##### method: `fromMinMax()`

Creates a rectangle from two coordinate values.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:25` |
| Return 		 | <a href="../classes/Rect.html" class="crosslink">Rect</a> 

###### Parameters
- v1 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- v2 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `fromVec2()`

Creates a rectangle from left-top coordinate value and size.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:42` |
| Return 		 | <a href="../classes/Rect.html" class="crosslink">Rect</a> 

###### Parameters
- leftTop <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- size <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `intersects()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:203` |

###### Parameters
- rect <a href="../classes/Rect.html" class="crosslink">Rect</a>  


##### method: `lerp()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:103` |
| Return 		 | <a href="../classes/Rect.html" class="crosslink">Rect</a> 

###### Parameters
- to <a href="../classes/Rect.html" class="crosslink">Rect</a>  
- ratio <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> the interpolation coefficient
- out <a href="../classes/Rect.html" class="crosslink">Rect</a> optional, the receiving vector


##### method: `rect()`

The convenience method to create a new Rect

| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:254` |
| Return 		 | <a href="../classes/Rect.html" class="crosslink">Rect</a> 

###### Parameters
- x <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- y <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- w <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- h <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `toString()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/rect.js:123` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 





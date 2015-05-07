
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Vec2` Class


Defined in: [utils/api/core/vec2.js:6](../files/utils/api/core/vec2.js.js)

Module: [Fire](../modules/Fire.md)




Representation of 2D vectors and points.

see {% crosslink Fire.v2 Fire.v2 %}

### Index

##### Properties

  - `one`
  - `right`
  - `up`
  - `zero`



##### Methods

  - `Vec2` **constructor**
  - `add`
  - `addSelf`
  - `angle`
  - `clone`
  - `cross`
  - `div`
  - `divSelf`
  - `dot`
  - `equals`
  - `lerp`
  - `mag`
  - `magSqr`
  - `mul`
  - `mulSelf`
  - `neg`
  - `negSelf`
  - `normalize`
  - `normalizeSelf`
  - `rotate`
  - `rotateSelf`
  - `scale`
  - `scaleSelf`
  - `set`
  - `signAngle`
  - `sub`
  - `subSelf`
  - `toString`
  - `v2`





### Details


#### Properties



##### property: `one`

return a Vec2 object with x = 1 and y = 1

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/core/vec2.js:23` |




##### property: `right`

return a Vec2 object with x = 1 and y = 0

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/core/vec2.js:59` |




##### property: `up`

return a Vec2 object with x = 0 and y = 1

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/core/vec2.js:47` |




##### property: `zero`

return a Vec2 object with x = 0 and y = 0

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/core/vec2.js:35` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Vec2()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:6` |

###### Parameters
- x <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- y <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `add()`

Adds tow vectors, and returns the new result.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:144` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `addSelf()`

Adds this vector. If you want to save result to another vector, use add() instead.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:131` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `angle()`

Get angle in radian between this and vector

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:368` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `clone()`


 clone a Vec2 value


| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:73` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 



##### method: `cross()`

Cross product

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:301` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `div()`

Divides two vectors, and returns the new result.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:252` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `divSelf()`

Divides two vectors. If you want to save result to another vector, use div() instead.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:239` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `dot()`

Dot product

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:291` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `equals()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:95` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- other <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `lerp()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:115` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- to <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- ratio <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> the interpolation coefficient
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `mag()`

Returns the length of this vector.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:311` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 



##### method: `magSqr()`

Returns the squared length of this vector.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:320` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 



##### method: `mul()`

Multiplies by a number, and returns the new result.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:198` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- num <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `mulSelf()`

Multiplies this by a number. If you want to save result to another vector, use mul() instead.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:185` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- num <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `neg()`

Negates the components, and returns the new result.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:278` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `negSelf()`

Negates the components. If you want to save result to another vector, use neg() instead.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:266` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 



##### method: `normalize()`

Returns this vector with a magnitude of 1.

Note that the current vector is unchanged and a new normalized vector is returned. If you want to normalize the current vector, use normalizeSelf function.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:352` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `normalizeSelf()`

Make the length of this vector to 1.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:329` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 



##### method: `rotate()`

rotate

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:404` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- radians <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `rotateSelf()`

rotate self

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:418` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- radians <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `scale()`

Multiplies two vectors, and returns the new result.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:225` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `scaleSelf()`

Multiplies two vectors.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:212` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `set()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:83` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- newValue <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 
 new value to set. 


##### method: `signAngle()`

Get angle in radian between this and vector with direction

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:389` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `sub()`

Subtracts one vector from this, and returns the new result.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:171` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `subSelf()`

Subtracts one vector from this. If you want to save result to another vector, use sub() instead.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:158` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `toString()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:104` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 



##### method: `v2()`

The convenience method to create a new {% crosslink Vec2 Vec2 %}

| meta | description |
|------|-------------|
| Defined | `utils/api/core/vec2.js:442` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- x <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- y <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  




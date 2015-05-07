
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Matrix23` Class


Defined in: [utils/api/core/matrix23.js:4](../files/utils/api/core/matrix23.js.js)

Module: [Fire](../modules/Fire.md)




Simple matrix to do 2D affine transformations.
It is actually 3x3 but the last row is [0 0 1].

### Index

##### Properties

  - `a`
  - `b`
  - `c`
  - `d`
  - `identity`
  - `tx`
  - `ty`



##### Methods

  - `Matrix23` **constructor**
  - `clone`
  - `clone`
  - `equals`
  - `getRotation`
  - `getScale`
  - `getTranslation`
  - `getTRS`
  - `identity`
  - `invert`
  - `prepend`
  - `rotate`
  - `setScale`
  - `toString`
  - `transformPoint`





### Details


#### Properties



##### property: `a`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/matrix23.js:11` |
| Default    | 1 |




##### property: `b`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/matrix23.js:18` |
| Default    | 0 |




##### property: `c`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/matrix23.js:25` |
| Default    | 0 |




##### property: `d`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/matrix23.js:32` |
| Default    | 1 |




##### property: `identity`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> |
| Defined | `utils/api/core/matrix23.js:56` |




##### property: `tx`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/matrix23.js:39` |
| Default    | 0 |




##### property: `ty`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/matrix23.js:46` |
| Default    | 0 |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Matrix23()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:4` |



##### method: `clone()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:63` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 



##### method: `clone()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:78` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- other <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a>  


##### method: `equals()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:94` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- other <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a>  


##### method: `getRotation()`

Get rotation of this matrix.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:273` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 



##### method: `getScale()`

Get scaling of this matrix.

NOTE: negative scaling (mirroring) is not supported

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:209` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `getTranslation()`

Get translation of this matrix.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:288` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 



##### method: `getTRS()`

Extract translation, rotation and scaling component from this matrix.
Only support negative(mirroring) scaling in some special case.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:224` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 



##### method: `identity()`

Reset this matrix to identity.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:119` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 



##### method: `invert()`

Invert this matrix.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:165` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 



##### method: `prepend()`

Prepend this matrix.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:135` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- other <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a>  


##### method: `rotate()`

Rotate this matrix by counterclockwise.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:300` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- radians <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `setScale()`

Set scaling of this matrix.

NOTE: Can not scale negative scaling (mirroring) and zero scaling matrix.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:253` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- scale <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `toString()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:109` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 



##### method: `transformPoint()`

Apply transforms to given vector

| meta | description |
|------|-------------|
| Defined | `utils/api/core/matrix23.js:187` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- vector <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector




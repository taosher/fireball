
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Transform` Class

Extends `Component`

Defined in: [utils/api/engine/transform.js:6](../files/utils/api/engine/transform.js.js)

Module: [Fire](../modules/Fire.md)




Defines position, rotation and scale of an entity.

### Index

##### Properties

  - `_parent`
  - `_position;`
  - `_scale;`
  - `position`
  - `right`
  - `rotation`
  - `scale`
  - `scaleX`
  - `scaleY`
  - `up`
  - `worldPosition`
  - `worldRotation`
  - `worldScale`
  - `worldX`
  - `worldY`
  - `x`
  - `y`



##### Methods

  - `Transform` **constructor**
  - `getLocalMatrix`
  - `getLocalToWorldMatrix`
  - `getWorldToLocalMatrix`
  - `rotateAround`
  - `translate`




### Inherited members

##### Properties

- `entity`
- `_enabled`
- `enabled`
- `enabledInHierarchy`
- `transform`
- `isOnLoadCalled`
- `_hashCode`
- `_id`
- `hashCode`
- `id`
- `_name`
- `_objFlags`
- `name`
- `isValid`

##### Attributes


##### Methods

- `addComponent
- `getComponent
- `addComponentMenu
- `executeInEditMode
- `destroy
- `_destruct
- `_onPreDestroy
- `_serialize
- `_deserialize
- `isValid

##### Events

- `update
- `lateUpdate
- `onLoad
- `start
- `onEnable
- `onDisable
- `onDestroy
- `onPreRender



### Details


#### Properties



##### property: `_parent`

the cached reference to parent transform

| meta | description |
|------|-------------|
| Type | <a href="../classes/Transform.html" class="crosslink">Transform</a> |
| Defined | `utils/api/engine/transform.js:31` |
| Default    | null |




##### property: `_position;`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:14` |
| Default    | new Vec2(0, 0) |




##### property: `_scale;`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:21` |
| Default    | new Vec2(1, 1) |




##### property: `position`

The local position in its parent's coordinate system

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:53` |
| Default    | new Vec2(0, 0) |




##### property: `right`

right direction in world space, point to the x(red) axis

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:555` |




##### property: `rotation`

The counterclockwise degrees of rotation relative to the parent

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:230` |
| Default    | 0 |




##### property: `scale`

The local scale factor relative to the parent

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:281` |
| Default    | new Vec2(1, 1) |




##### property: `scaleX`

The local x scale factor relative to the parent

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:305` |
| Default    | 1 |




##### property: `scaleY`

The local y scale factor relative to the parent

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:329` |
| Default    | 1 |




##### property: `up`

up direction in world space, point to the y(green) axis

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:536` |




##### property: `worldPosition`

The position of the transform in world space

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:125` |
| Default    | new Vec2(0, 0) |




##### property: `worldRotation`

The counterclockwise degrees of rotation in world space

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:251` |
| Default    | 0 |




##### property: `worldScale`

The lossy scale of the transform in world space (Read Only)

| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/engine/transform.js:353` |
| Default    | new Vec2(1, 1) |




##### property: `worldX`

The x position of the transform in world space

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:154` |
| Default    | 0 |




##### property: `worldY`

The y position of the transform in world space

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:195` |
| Default    | 0 |




##### property: `x`

The local x position in its parent's coordinate system

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:77` |
| Default    | 0 |




##### property: `y`

The local y position in its parent's coordinate system

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/transform.js:101` |
| Default    | 0 |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Transform()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/transform.js:6` |



##### method: `getLocalMatrix()`

Get the local matrix that transforms a point from local space into parents space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/transform.js:445` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- out <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> optional, the receiving vector


##### method: `getLocalToWorldMatrix()`

Get the world transform matrix that transforms a point from local space into world space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/transform.js:485` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- out <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> optional, the receiving vector


##### method: `getWorldToLocalMatrix()`

Get the inverse world transform matrix that transforms a point from world space into local space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/transform.js:502` |
| Return 		 | <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> 

###### Parameters
- out <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> optional, the receiving vector


##### method: `rotateAround()`

Rotates this transform through point in world space by angle degrees.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/transform.js:512` |

###### Parameters
- point <a href="../classes/Vec2.html" class="crosslink">Vec2</a> the world point rotates through
- angle <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> degrees


##### method: `translate()`

Moves the transform in the direction and distance of translation. The movement is applied relative to the
transform's local space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/transform.js:525` |

###### Parameters
- translation <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  




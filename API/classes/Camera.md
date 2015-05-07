
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Camera` Class

Extends `Component`

Defined in: [utils/api/engine/camera.js:4](../files/utils/api/engine/camera.js.js)

Module: [Fire](../modules/Fire.md)




 

### Index

##### Properties

  - `background`
  - `contentStrategy`
  - `renderContext`
  - `size`
  - `viewportInfo`



##### Methods

  - `Camera` **constructor**
  - `screenToViewport`
  - `screenToWorld`
  - `viewportToScreen`
  - `viewportToWorld`
  - `worldToScreen`
  - `worldToViewport`




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



##### property: `background`

The color of the screen background.

| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/engine/camera.js:21` |
| Default    | Fire.Color.black |




##### property: `contentStrategy`

The Content Strategy of the camera.

| meta | description |
|------|-------------|
| Type | <a href="../classes/ContentStrategyType.html" class="crosslink">ContentStrategyType</a> |
| Defined | `utils/api/engine/camera.js:65` |
| Default    | Fire.ContentStrategyType.FixedHeight |




##### property: `renderContext`

save the render context this camera belongs to, if null, main render context will be used.

| meta | description |
|------|-------------|
| Type | <a href="../classes/_Runtime.RenderContext.html" class="crosslink">_Runtime.RenderContext</a> |
| Defined | `utils/api/engine/camera.js:97` |




##### property: `size`

The height of Design Resolution in pixels

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/camera.js:41` |
| Default    | 800 |




##### property: `viewportInfo`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined | `utils/api/engine/camera.js:84` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Camera()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:4` |



##### method: `screenToViewport()`

Transforms position from screen space into viewport space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:157` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- position <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `screenToWorld()`

Transforms position from screen space into world space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:188` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- position <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `viewportToScreen()`

Transforms position from viewport space into screen space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:141` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- position <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `viewportToWorld()`

Transforms position from viewport space into world space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:176` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- position <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `worldToScreen()`

Transforms position from world space into screen space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:208` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- position <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector


##### method: `worldToViewport()`

Transforms position from world space into viewport space.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/camera.js:226` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- position <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- out <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the receiving vector




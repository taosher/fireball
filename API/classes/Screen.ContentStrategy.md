
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Screen.ContentStrategy` Class


Defined in: [utils/api/engine/screen–agnostic.js:237](../files/utils/api/engine/screen–agnostic.js.js)

Module: [Fire](../modules/Fire.md)




ContentStrategy class is the root strategy class of content's scale strategy,
it controls the behavior of how to scale the scene and setup the viewport for the game.

### Index



##### Methods

  - `Screen.ContentStrategy` **constructor**
  - `apply`
  - `buildResult`
  - `getContainerSize`





### Details




<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Screen.ContentStrategy()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/screen–agnostic.js:237` |



##### method: `apply()`

Function to apply this strategy

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/screen–agnostic.js:111` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 

###### Parameters
- designedResolution <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `buildResult()`

Helper function for apply.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/screen–agnostic.js:120` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 

###### Parameters
- container <a href="../classes/Vec2.html" class="crosslink">Vec2</a> size of container
- content <a href="../classes/Vec2.html" class="crosslink">Vec2</a> size of content
- scale <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `getContainerSize()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/screen–agnostic.js:155` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 





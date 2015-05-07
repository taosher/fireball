
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Renderer` Class

Extends `HashObject`

Defined in: [utils/api/engine/renderer.js:6](../files/utils/api/engine/renderer.js.js)

Module: [Fire](../modules/Fire.md)




The base for all renderer

### Index



##### Methods

  - `Renderer` **constructor**
  - `getSelfMatrix`
  - `getWorldBounds`
  - `getWorldOrientedBounds`
  - `getWorldSize`
  - `onPreRender`




### Inherited members

##### Properties

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

- `destroy
- `_destruct
- `_onPreDestroy
- `_serialize
- `_deserialize
- `isValid

##### Events




### Inheritance tree


### Details




<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Renderer()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/renderer.js:6` |



##### method: `getSelfMatrix()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/renderer.js:69` |

###### Parameters
- out <a href="../classes/Matrix23.html" class="crosslink">Matrix23</a> the receiving matrix


##### method: `getWorldBounds()`

Returns a "world" axis aligned bounding box(AABB) of the renderer.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/renderer.js:33` |
| Return 		 | <a href="../classes/Rect.html" class="crosslink">Rect</a> 

###### Parameters
- out <a href="../classes/Rect.html" class="crosslink">Rect</a> optional, the receiving rect


##### method: `getWorldOrientedBounds()`

Returns a "world" oriented bounding box(OBB) of the renderer.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/renderer.js:48` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 

###### Parameters
- out_bl <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the vector to receive the world position of bottom left
- out_tl <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the vector to receive the world position of top left
- out_tr <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the vector to receive the world position of top right
- out_br <a href="../classes/Vec2.html" class="crosslink">Vec2</a> optional, the vector to receive the world position of bottom right


##### method: `getWorldSize()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/renderer.js:79` |
| Return 		 | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> 



##### method: `onPreRender()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/renderer.js:87` |





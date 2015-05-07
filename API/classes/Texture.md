
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Texture` Class

Extends `Asset`

Defined in: [utils/api/core/texture.js:65](../files/utils/api/core/texture.js.js)

Module: [Fire](../modules/Fire.md)




Class for texture handling.
Use this to create textures on the fly or to modify existing texture assets.

### Index

##### Properties

  - `filterMode`
  - `height`
  - `image`
  - `width`
  - `wrapMode`



##### Methods

  - `Texture` **constructor**
  - `getPixel`




### Inherited members

##### Properties

- `_uuid`
- `dirty`
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

- `_setRawExtname
- `destroy
- `_destruct
- `_onPreDestroy
- `_serialize
- `_deserialize
- `isValid

##### Events




### Details


#### Properties



##### property: `filterMode`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Texture.FilterMode.html" class="crosslink">Texture.FilterMode</a> |
| Defined | `utils/api/core/texture.js:88` |




##### property: `height`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/texture.js:78` |




##### property: `image`



| meta | description |
|------|-------------|
| Type | Image |
| Defined | `utils/api/core/texture.js:68` |




##### property: `width`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/texture.js:73` |




##### property: `wrapMode`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Texture.WrapMode.html" class="crosslink">Texture.WrapMode</a> |
| Defined | `utils/api/core/texture.js:83` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Texture()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/texture.js:65` |

###### Parameters
- img Image the html image element to render


##### method: `getPixel()`

Returns pixel color at coordinates (x, y).

If the pixel coordinates are out of bounds (larger than width/height or small than 0),
they will be clamped or repeated based on the texture's wrap mode.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/texture.js:99` |
| Return 		 | Fire.Color 

###### Parameters
- x <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- y <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  




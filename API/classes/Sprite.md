
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Sprite` Class

Extends `Asset`

Defined in: [utils/api/core/sprite.js:6](../files/utils/api/core/sprite.js.js)

Module: [Fire](../modules/Fire.md)




Represents a Sprite object which obtained from Texture.

### Index

##### Properties

  - `alphaThreshold`
  - `height`
  - `pivot`
  - `pixelLevelHitTest`
  - `rawHeight`
  - `rawWidth`
  - `rotated`
  - `rotatedHeight`
  - `rotatedWidth`
  - `texture`
  - `trimX`
  - `trimY`
  - `width`
  - `x`
  - `y`






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



##### property: `alphaThreshold`

The highest alpha channel value that is considered opaque for hit test. [0, 1]

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:103` |
| Default    | 0.1 |




##### property: `height`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:48` |




##### property: `pivot`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Vec2.html" class="crosslink">Vec2</a> |
| Defined | `utils/api/core/sprite.js:22` |
| Default    | new Fire.Vec2(0.5, 0.5) |




##### property: `pixelLevelHitTest`

Use pixel-level hit testing.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/core/sprite.js:95` |
| Default    | false |




##### property: `rawHeight`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:89` |




##### property: `rawWidth`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:83` |




##### property: `rotated`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/core/sprite.js:60` |
| Default    | false |




##### property: `rotatedHeight`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:125` |




##### property: `rotatedWidth`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:116` |




##### property: `texture`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Texture.html" class="crosslink">Texture</a> |
| Defined | `utils/api/core/sprite.js:54` |




##### property: `trimX`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:33` |




##### property: `trimY`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:38` |




##### property: `width`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:43` |




##### property: `x`

uv of the sprite in atlas-texture

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:69` |




##### property: `y`

uv of the sprite in atlas-texture

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/sprite.js:76` |








# fireball-build 0.3.0

Fireball is the game engine for the future.

### `InputField` Class

Extends `Renderer`

Defined in: [utils/api/engine/input-field.js:25](../files/utils/api/engine/input-field.js.js)

Module: [Fire](../modules/Fire.md)




The Input Field renderer component.

### Index

##### Properties

  - `anchor`
  - `background`
  - `color`
  - `customFontType`
  - `fontFlagType`
  - `fontType`
  - `maxLength`
  - `size`
  - `text`






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

- `getWorldBounds
- `getWorldOrientedBounds
- `getSelfMatrix
- `getWorldSize
- `onPreRender
- `destroy
- `_destruct
- `_onPreDestroy
- `_serialize
- `_deserialize
- `isValid

##### Events




### Details


#### Properties



##### property: `anchor`

The anchor point of the input field.

| meta | description |
|------|-------------|
| Type | Fire.TextAnchor |
| Defined | `utils/api/engine/input-field.js:185` |
| Default    | Fire.TextAnchor.midCenter |




##### property: `background`

The background of the inputField.

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteRenderer.html" class="crosslink">SpriteRenderer</a> |
| Defined | `utils/api/engine/input-field.js:40` |
| Default    | null |




##### property: `color`

The color of input text.

| meta | description |
|------|-------------|
| Type | <a href="../classes/Color.html" class="crosslink">Color</a> |
| Defined | `utils/api/engine/input-field.js:168` |
| Default    | Fire.Color.black |




##### property: `customFontType`

The custom font type of the input text.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/engine/input-field.js:77` |
| Default    | &quot;Arial&quot; |




##### property: `fontFlagType`

The font flag Type of the input text.

| meta | description |
|------|-------------|
| Type | <a href="../classes/FontFlagType.html" class="crosslink">FontFlagType</a> |
| Defined | `utils/api/engine/input-field.js:101` |
| Default    | FontFlagType.Text |




##### property: `fontType`

The font type of the input text.

| meta | description |
|------|-------------|
| Type | <a href="../classes/FontType.html" class="crosslink">FontType</a> |
| Defined | `utils/api/engine/input-field.js:60` |
| Default    | FontType.Arial |




##### property: `maxLength`

The maxLength of input text.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-field.js:152` |
| Default    | 10 |




##### property: `size`

The size of input text.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-field.js:136` |
| Default    | 20 |




##### property: `text`

The text of input field.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/engine/input-field.js:118` |
| Default    | &quot;Enter text...&quot; |







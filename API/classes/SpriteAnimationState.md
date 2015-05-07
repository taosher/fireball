
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `SpriteAnimationState` Class


Defined in: [utils/api/builtin/sprite-animation/sprite-animation-state.js:6](../files/utils/api/builtin/sprite-animation/sprite-animation-state.js.js)

Module: [Fire](../modules/Fire.md)




The sprite animation state.

### Index

##### Properties

  - `clip`
  - `length`
  - `name`
  - `speed`
  - `stopAction`
  - `totalFrames`
  - `wrapMode`



##### Methods

  - `SpriteAnimationState` **constructor**
  - `getCurrentIndex`





### Details


#### Properties



##### property: `clip`

The referenced sprite animation clip

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.html" class="crosslink">SpriteAnimationClip</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:25` |




##### property: `length`

The length of the sprite animation in seconds with speed = 1.0f

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:57` |




##### property: `name`

The name of the sprite animation state.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:19` |




##### property: `speed`

The speed to play the sprite animation clip

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:43` |




##### property: `stopAction`

The stop action

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.StopAction.html" class="crosslink">SpriteAnimationClip.StopAction</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:37` |




##### property: `totalFrames`

The total frame count of the sprite animation clip

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:51` |




##### property: `wrapMode`

The wrap mode

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.WrapMode.html" class="crosslink">SpriteAnimationClip.WrapMode</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:31` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `SpriteAnimationState()`



| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:6` |

###### Parameters
- animClip <a href="../classes/SpriteAnimationClip.html" class="crosslink">SpriteAnimationClip</a>  


##### method: `getCurrentIndex()`

The current frame info index.

| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-state.js:72` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 





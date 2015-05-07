
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `SpriteAnimationClip` Class

Extends `CustomAsset`

Defined in: [utils/api/builtin/sprite-animation/sprite-animation-clip.js:82](../files/utils/api/builtin/sprite-animation/sprite-animation-clip.js.js)

Module: [Fire](../modules/Fire.md)




The sprite animation clip.

### Index

##### Properties

  - `frameInfos`
  - `frameRate`
  - `speed`
  - `stopAction`
  - `wrapMode`






### Inherited members

##### Properties


##### Attributes


##### Methods


##### Events




### Details


#### Properties



##### property: `frameInfos`

The frame infos in the sprite animation clips.
are array of {sprite: Sprite, frames: Sustained_how_many_frames}

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object[]</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-clip.js:144` |
| Default    | [] |




##### property: `frameRate`

The sample rate used in this animation clip.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-clip.js:128` |
| Default    | 60 |




##### property: `speed`

The default speed of the animation clip.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-clip.js:119` |
| Default    | 1 |




##### property: `stopAction`

The default type of action used when the animation stopped.

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.StopAction.html" class="crosslink">SpriteAnimationClip.StopAction</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-clip.js:109` |
| Default    | SpriteAnimationClip.StopAction.DoNothing |




##### property: `wrapMode`

Default wrap mode.

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.WrapMode.html" class="crosslink">SpriteAnimationClip.WrapMode</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation-clip.js:99` |
| Default    | SpriteAnimationClip.WrapMode.Default |








# fireball-build 0.3.0

Fireball is the game engine for the future.

### `SpriteAnimation` Class

Extends `Component`

Defined in: [utils/api/builtin/sprite-animation/sprite-animation.js:7](../files/utils/api/builtin/sprite-animation/sprite-animation.js.js)

Module: [Fire](../modules/Fire.md)




The sprite animation Component.

### Index

##### Properties

  - `animations`
  - `defaultAnimation`
  - `playAutomatically`



##### Methods

  - `SpriteAnimation` **constructor**
  - `getAnimState`
  - `isPlaying`
  - `play`
  - `stop`




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



##### property: `animations`

The Animated clip list.

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.html" class="crosslink">SpriteAnimationClip[]</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:40` |
| Default    | [] |




##### property: `defaultAnimation`

The default animation.

| meta | description |
|------|-------------|
| Type | <a href="../classes/SpriteAnimationClip.html" class="crosslink">SpriteAnimationClip</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:30` |
| Default    | null |




##### property: `playAutomatically`

Should the default animation clip (Animation.clip) automatically start playing on startup.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:52` |
| Default    | true |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `SpriteAnimation()`



| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:7` |



##### method: `getAnimState()`

Get Animation State.

| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:90` |
| Return 		 | <a href="../classes/SpriteAnimationState.html" class="crosslink">SpriteAnimationState</a> 

###### Parameters
- animName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> The name of the animation


##### method: `isPlaying()`

Indicates whether the animation is playing

| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:99` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- name <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> The name of the animation


##### method: `play()`

Play Animation

| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:109` |

###### Parameters
- animState <a href="../classes/SpriteAnimationState.html" class="crosslink">SpriteAnimationState</a> The animState of the sprite Animation state or animation name
- time <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> The time of the animation time


##### method: `stop()`

Stop Animation

| meta | description |
|------|-------------|
| Defined | `utils/api/builtin/sprite-animation/sprite-animation.js:130` |

###### Parameters
- animState <a href="../classes/SpriteAnimationState.html" class="crosslink">SpriteAnimationState</a> The animState of the sprite animation state or animation name




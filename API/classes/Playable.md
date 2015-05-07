
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Playable` Class


Defined in: [utils/api/engine/playable.js:5](../files/utils/api/engine/playable.js.js)

Module: [Fire](../modules/Fire.md)




 

### Index

##### Properties

  - `isPaused`
  - `isPlaying`
  - `isUpdating`



##### Methods

  - `Playable` **constructor**
  - `onError`
  - `onPause`
  - `onPlay`
  - `onResume`
  - `onStop`
  - `pause`
  - `play`
  - `step`
  - `stop`





### Details


#### Properties



##### property: `isPaused`

Is currently paused? This can be true even if in edit mode(isPlaying == false).

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/playable.js:46` |
| Default    | false |




##### property: `isPlaying`

Is playing?
This property ignores the paused state, so even it is currently paused, this property still true.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/playable.js:20` |
| Default    | false |




##### property: `isUpdating`

Is currently updating?
This property is just the result of (this.isPlaying == true && this.isPaused == false)

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/playable.js:33` |
| Default    | false |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Playable()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:5` |



##### method: `onError()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:80` |

###### Parameters
- errorCode <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `onPause()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:65` |



##### method: `onPlay()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:60` |



##### method: `onResume()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:70` |



##### method: `onStop()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:75` |



##### method: `pause()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:126` |



##### method: `play()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:89` |



##### method: `step()`

Perform a single frame step.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:136` |



##### method: `stop()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/playable.js:113` |





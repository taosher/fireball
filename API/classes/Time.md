
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Time` Class


Defined in: [utils/api/engine/time.js:4](../files/utils/api/engine/time.js.js)

Module: [Fire](../modules/Fire.md)





 The interface to get time information from Fireball.

See [Time](/en/scripting/time/)


### Index

##### Properties

  - `deltaTime`
  - `frameCount`
  - `maxDeltaTime`
  - `realTime`
  - `time`



##### Methods

  - `Fire.Time._update`





### Details


#### Properties



##### property: `deltaTime`

The time in seconds it took to complete the last frame. Use this property to make your game frame rate independent.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/time.js:36` |




##### property: `frameCount`

The total number of frames that have passed.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/time.js:44` |




##### property: `maxDeltaTime`

The maximum time a frame can take.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/time.js:52` |




##### property: `realTime`

The time at the beginning of this frame. This is the real time in seconds since the start of the game.

`Time.realTime` not affected by time scale, and also keeps increasing while the player is paused in editor or in the background.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/time.js:26` |




##### property: `time`

The time at the beginning of this frame. This is the time in seconds since the start of the game.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/time.js:18` |






<!-- Method Block -->
#### Methods


##### method: `Fire.Time._update()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/time.js:63` |

###### Parameters
- timestamp <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- paused <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> if true, only realTime will be updated
- maxDeltaTime <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  




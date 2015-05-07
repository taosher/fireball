
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `AnimationNode` Class


Defined in: [utils/api/engine/animation-data-types.js:145](../files/utils/api/engine/animation-data-types.js.js)

Module: [Fire](../modules/Fire.md)




The collection and instance of AnimClips.

### Index

##### Properties

  - `_timeNoScale`
  - `curves`
  - `delay`
  - `direction`
  - `duration`
  - `iterations`
  - `playbackRate`
  - `time`







### Details


#### Properties



##### property: `_timeNoScale`

The local time, just used for delay

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/animation-data-types.js:204` |
| Default    | 0 |




##### property: `curves`



| meta | description |
|------|-------------|
| Type | <a href="../classes/AnimCurve.html" class="crosslink">AnimCurve[]</a> |
| Defined | `utils/api/engine/animation-data-types.js:234` |




##### property: `delay`


 The start delay which represents the number of seconds from an animation's start time to the start of
the active interval.


| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/animation-data-types.js:242` |
| Default    | 0 |




##### property: `direction`

The playback direction of the animation as specified by one of the PlaybackDirection enumeration values.

| meta | description |
|------|-------------|
| Type | <a href="../classes/PlaybackDirection.html" class="crosslink">PlaybackDirection</a> |
| Defined | `utils/api/engine/animation-data-types.js:288` |
| Default    | : Fire.PlaybackDirection.normal |




##### property: `duration`


 The iteration duration of this animation in seconds. (length)


| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/animation-data-types.js:270` |




##### property: `iterations`


 The animation's iteration count property.

A real number greater than or equal to zero (including positive infinity) representing the number of times
to repeat the animation node.

Values less than zero and NaN values are treated as the value 1.0 for the purpose of timing model
calculations.



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/animation-data-types.js:253` |
| Default    | 1 |




##### property: `playbackRate`


 The animation's playback rate property. (speed)


| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/animation-data-types.js:279` |
| Default    | : 1.0 |




##### property: `time`

The active time of this animation, not include delay.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/animation-data-types.js:195` |
| Default    | 0 |







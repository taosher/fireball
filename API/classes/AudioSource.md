
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `AudioSource` Class

Extends `Component`

Defined in: [utils/api/engine/audio-source.js:7](../files/utils/api/engine/audio-source.js.js)

Module: [Fire](../modules/Fire.md)




The audio source component.

### Index

##### Properties

  - `clip`
  - `isPaused`
  - `isPlaying`
  - `loop`
  - `mute`
  - `onEnd`
  - `playbackRate`
  - `playOnLoad`
  - `time`
  - `volume`



##### Methods

  - `AudioSource` **constructor**
  - `pause`
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



##### property: `clip`

The audio clip to play.

| meta | description |
|------|-------------|
| Type | <a href="../classes/AudioClip.html" class="crosslink">AudioClip</a> |
| Defined | `utils/api/engine/audio-source.js:85` |
| Default    | null |




##### property: `isPaused`

Is the audio source paused (Read Only)?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/audio-source.js:53` |
| Default    | false |




##### property: `isPlaying`

Is the audio source playing (Read Only)？

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/audio-source.js:40` |
| Default    | false |




##### property: `loop`

Is the audio source looping?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/audio-source.js:104` |
| Default    | false |




##### property: `mute`

Is the audio source mute?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/audio-source.js:123` |
| Default    | false |




##### property: `onEnd`

The callback function which will be invoked when the audio stops

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> |
| Defined | `utils/api/engine/audio-source.js:31` |
| Default    | null |




##### property: `playbackRate`

The playback rate of the audio source.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/audio-source.js:162` |
| Default    | 1 |




##### property: `playOnLoad`

If set to true, the audio source will automatically start playing on onLoad.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/audio-source.js:181` |
| Default    | true |




##### property: `time`

Playback position in seconds.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/audio-source.js:66` |
| Default    | 0 |




##### property: `volume`

The volume of the audio source.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/audio-source.js:142` |
| Default    | 1 |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `AudioSource()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/audio-source.js:7` |



##### method: `pause()`

Pauses the clip.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/audio-source.js:197` |



##### method: `play()`

Plays the clip.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/audio-source.js:208` |



##### method: `stop()`

Stops the clip

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/audio-source.js:224` |





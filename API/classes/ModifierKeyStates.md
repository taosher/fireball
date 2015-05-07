
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `ModifierKeyStates` Class


Defined in: [utils/api/engine/input-events.js:7](../files/utils/api/engine/input-events.js.js)

Module: [Fire](../modules/Fire.md)




 

### Index

##### Properties

  - `altKey`
  - `ctrlKey`
  - `metaKey`
  - `nativeEvent`
  - `shiftKey`



##### Methods

  - `ModifierKeyStates` **constructor**
  - `_reset`
  - `getModifierState`
  - `initFromNativeEvent`





### Details


#### Properties



##### property: `altKey`

Returns true if the `alt` key was down when the event was fired.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/input-events.js:36` |




##### property: `ctrlKey`

Returns true if the `ctrl` key was down when the event was fired.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/input-events.js:24` |




##### property: `metaKey`

Returns true if the `meta` key was down when the event was fired.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/input-events.js:42` |




##### property: `nativeEvent`



| meta | description |
|------|-------------|
| Type | UIEvent |
| Defined | `utils/api/engine/input-events.js:17` |




##### property: `shiftKey`

Returns true if the `shift` key was down when the event was fired.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/input-events.js:30` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `ModifierKeyStates()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/input-events.js:7` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> The name of the event (case-sensitive), e.g. "click", "fire", or "submit".
- nativeEvent UIEvent The native event object attaching to this event object.


##### method: `_reset()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/input-events.js:78` |



##### method: `getModifierState()`

Returns the current state of the specified modifier key. true if the modifier is active (i.e., the modifier key is pressed or locked). Otherwise, false.

See https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent.getModifierState

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/input-events.js:51` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- keyArg <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> A modifier key value. The value must be one of the KeyboardEvent.key values which represent modifier keys or "Accel". This is case-sensitive.
                         NOTE: If an application wishes to distinguish between right and left modifiers, this information could be deduced using keyboard events and Fire.KeyboardEvent.location.


##### method: `initFromNativeEvent()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/input-events.js:65` |

###### Parameters
- nativeEvent UIEvent The original DOM event




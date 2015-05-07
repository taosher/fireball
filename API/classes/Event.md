
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Event` Class


Defined in: [utils/api/engine/event.js:6](../files/utils/api/engine/event.js.js)

Module: [Fire](../modules/Fire.md)




An event allows for signaling that something has occurred. E.g. that an asset has completed downloading.

### Index

##### Properties

  - `_defaultPrevented`
  - `_propagationImmediateStopped`
  - `_propagationStopped`
  - `AT_TARGET`
  - `bubbles`
  - `BUBBLING_PHASE`
  - `CAPTURING_PHASE`
  - `currentTarget;`
  - `eventPhase`
  - `NONE`
  - `target`
  - `type`



##### Methods

  - `Event` **constructor**
  - `_reset`
  - `preventDefault`
  - `stop`





### Details


#### Properties



##### property: `_defaultPrevented`

Indicates whether or not event.preventDefault() has been called on the event

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/event.js:60` |




##### property: `_propagationImmediateStopped`

Indicates whether or not event.stop(true) has been called on the event

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/event.js:76` |




##### property: `_propagationStopped`

Indicates whether or not event.stop() has been called on the event

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/event.js:68` |




##### property: `AT_TARGET`

The target phase comprises only the event target node
see http://www.w3.org/TR/DOM-Level-3-Events/#event-flow

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/event.js:109` |




##### property: `bubbles`

A boolean indicating whether the event bubbles up through the hierarchy or not

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/event.js:53` |




##### property: `BUBBLING_PHASE`

The bubbling phase comprises any subsequent nodes encountered on the return trip to the root of the hierarchy
see http://www.w3.org/TR/DOM-Level-3-Events/#event-flow

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/event.js:118` |




##### property: `CAPTURING_PHASE`

The capturing phase comprises the journey from the root to the last node before the event target's node
see http://www.w3.org/TR/DOM-Level-3-Events/#event-flow

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/event.js:100` |




##### property: `currentTarget;`

A reference to the currently registered target for the event

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined | `utils/api/engine/event.js:31` |




##### property: `eventPhase`

Indicates which phase of the event flow is currently being evaluated.
Returns an integer value represented by 4 constants:
 - Event.NONE = 0
 - Event.CAPTURING_PHASE = 1
 - Event.AT_TARGET = 2
 - Event.BUBBLING_PHASE = 3
The phases are explained in the [section 3.1, Event dispatch and DOM event flow]
(http://www.w3.org/TR/DOM-Level-3-Events/#event-flow), of the DOM Level 3 Events specification.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/event.js:38` |




##### property: `NONE`

Events not currently dispatched are in this phase

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/event.js:92` |




##### property: `target`

A reference to the target to which the event was originally dispatched

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined | `utils/api/engine/event.js:24` |




##### property: `type`

The name of the event (case-sensitive), e.g. "click", "fire", or "submit"

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/engine/event.js:17` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Event()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event.js:6` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> The name of the event (case-sensitive), e.g. "click", "fire", or "submit"
- bubbles <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> A boolean indicating whether the event bubbles up through the tree or not


##### method: `_reset()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event.js:152` |



##### method: `preventDefault()`

If invoked when the cancelable attribute value is true, signals to the operation that caused event to be dispatched that it needs to be canceled.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event.js:144` |



##### method: `stop()`

Stop propagation. When dispatched in a tree, invoking this method prevents event from reaching any other objects than the current.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event.js:128` |

###### Parameters
- immediate <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> Indicates whether or not to immediate stop the propagation, default is false.
                                     If true, for this particular event, no other callback will be called.
                                     Neither those attached on the same event target,
                                     nor those attached on targets which will be traversed later.




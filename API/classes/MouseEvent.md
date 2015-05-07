
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `MouseEvent` Class

Extends `ModifierKeyStates`

Defined in: [utils/api/engine/input-events.js:108](../files/utils/api/engine/input-events.js.js)

Module: [Fire](../modules/Fire.md)




The MouseEvent interface represents events that occur due to the user interacting with a pointing device (such as a mouse). Common events using this interface include click, dblclick, mouseup, mousedown.

See
- https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent
- http://www.quirksmode.org/dom/w3c_events.html#mousepos

### Index

##### Properties

  - `button`
  - `buttonStates`
  - `deltaX`
  - `deltaY`
  - `relatedTarget`
  - `screenX`
  - `screenY`






### Inherited members

##### Properties

- `nativeEvent`
- `ctrlKey`
- `shiftKey`
- `altKey`
- `metaKey`

##### Attributes


##### Methods

- `getModifierState
- `initFromNativeEvent
- `_reset

##### Events




### Details


#### Properties



##### property: `button`

Indicates which button was pressed on the mouse to trigger the event.

(0: Left button, 1: Wheel button or middle button (if present), 2: Right button)

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-events.js:125` |
| Default    | 0 |




##### property: `buttonStates`

Indicates which buttons were pressed on the mouse to trigger the event

See https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent.buttons

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-events.js:135` |
| Default    | 0 |




##### property: `deltaX`

The X coordinate of the mouse pointer relative to the position of the last mousemove event.
Not available for touch event.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-events.js:159` |




##### property: `deltaY`

The Y coordinate of the mouse pointer relative to the position of the last mousemove event.
Not available for touch event.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-events.js:167` |




##### property: `relatedTarget`

The secondary target for the event, if there is one.

| meta | description |
|------|-------------|
| Type | <a href="../classes/EventTarget.html" class="crosslink">EventTarget</a> |
| Defined | `utils/api/engine/input-events.js:175` |




##### property: `screenX`

The X coordinate of the mouse pointer in screen coordinates.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-events.js:145` |




##### property: `screenY`

The Y coordinate of the mouse pointer in screen coordinates.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/input-events.js:152` |







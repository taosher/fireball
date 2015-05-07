
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `EventTarget` Class

Extends `HashObject`

Defined in: [utils/api/engine/event-target.js:6](../files/utils/api/engine/event-target.js.js)

Module: [Fire](../modules/Fire.md)




EventTarget is an object to which an event is dispatched when something has occurred.
Entity are the most common event targets, but other objects can be event targets too.

Event targets are an important part of the Fireball event model.
The event target serves as the focal point for how events flow through the scene graph.
When an event such as a mouse click or a keypress occurs, Fireball dispatches an event object
into the event flow from the root of the hierarchy. The event object then makes its way through
the scene graph until it reaches the event target, at which point it begins its return trip through
the scene graph. This round-trip journey to the event target is conceptually divided into three phases:
- The capture phase comprises the journey from the root to the last node before the event target's node
- The target phase comprises only the event target node
- The bubbling phase comprises any subsequent nodes encountered on the return trip to the root of the tree
See also: http://www.w3.org/TR/DOM-Level-3-Events/#event-flow

Event targets can implement the following methods:
 - _getCapturingTargets
 - _getBubblingTargets

### Index

##### Properties

  - `_bubblingListeners`
  - `_capturingListeners`



##### Methods

  - `EventTarget` **constructor**
  - `_doSendEvent`
  - `dispatchEvent`
  - `emit`
  - `off`
  - `on`
  - `once`




### Inherited members

##### Properties

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

- `destroy
- `_destruct
- `_onPreDestroy
- `_serialize
- `_deserialize
- `isValid

##### Events




### Details


#### Properties



##### property: `_bubblingListeners`



| meta | description |
|------|-------------|
| Type | EventListeners |
| Defined | `utils/api/engine/event-target.js:40` |
| Default    | null |




##### property: `_capturingListeners`



| meta | description |
|------|-------------|
| Type | EventListeners |
| Defined | `utils/api/engine/event-target.js:32` |
| Default    | null |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `EventTarget()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:6` |



##### method: `_doSendEvent()`

Send an event to this object directly, this method will not propagate the event to any other objects.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:205` |

###### Parameters
- event <a href="../classes/Event.html" class="crosslink">Event</a> The Event object that is sent to this event target.


##### method: `dispatchEvent()`

Dispatches an event into the event flow. The event target is the EventTarget object upon which the dispatchEvent() method is called.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:189` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- event <a href="../classes/Event.html" class="crosslink">Event</a> The Event object that is dispatched into the event flow


##### method: `emit()`

Send an event to this object directly, this method will not propagate the event to any other objects.
The event will be created from the supplied message, you can get the "detail" argument from event.detail.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:227` |

###### Parameters
- message <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the message to send
- detail Any whatever argument the message needs


##### method: `off()`

Removes the callback previously registered with the same type, callback, and capture.
This method is merely an alias to removeEventListener.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:82` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> A string representing the event type being removed.
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> The callback to remove.
- useCapture <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> Specifies whether the callback being removed was registered as a capturing callback or not.
                             If not specified, useCapture defaults to false. If a callback was registered twice,
                             one with capture and one without, each must be removed separately. Removal of a capturing callback
                             does not affect a non-capturing version of the same listener, and vice versa.


##### method: `on()`

Register an callback of a specific event type on the EventTarget.
This method is merely an alias to addEventListener.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:50` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> A string representing the event type to listen for.
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> The callback that will be invoked when the event is dispatched.
                             The callback is ignored if it is a duplicate (the callbacks are unique).
	- param <a href="../classes/Event.html" class="crosslink">Event</a> event
- useCapture <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> When set to true, the capture argument prevents callback
                             from being invoked when the event's eventPhase attribute value is BUBBLING_PHASE.
                             When false, callback will NOT be invoked when event's eventPhase attribute value is CAPTURING_PHASE.
                             Either way, callback will be invoked when event's eventPhase attribute value is AT_TARGET.


##### method: `once()`

Register an callback of a specific event type on the EventTarget, the callback will remove itself after the first time it is triggered.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/event-target.js:105` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> A string representing the event type to listen for.
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> The callback that will be invoked when the event is dispatched.
                             The callback is ignored if it is a duplicate (the callbacks are unique).
	- param <a href="../classes/Event.html" class="crosslink">Event</a> event
- useCapture <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> When set to true, the capture argument prevents callback
                             from being invoked when the event's eventPhase attribute value is BUBBLING_PHASE.
                             When false, callback will NOT be invoked when event's eventPhase attribute value is CAPTURING_PHASE.
                             Either way, callback will be invoked when event's eventPhase attribute value is AT_TARGET.




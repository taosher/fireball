
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Input` Class


Defined in: [utils/api/engine/input.js:6](../files/utils/api/engine/input.js.js)

Module: [Fire](../modules/Fire.md)




Interface into the Input system.

### Index



##### Methods

  - `off`
  - `on`





### Details




<!-- Method Block -->
#### Methods


##### method: `off()`

Removes the callback previously registered with the same type and callback.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/input.js:52` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  


##### method: `on()`


 Register an callback of a specific input event type.

For all supported event and type, please see [Input Events](/en/scripting/input-events)



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/input.js:26` |

###### Parameters
- type <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> eg. "keydown", "click"
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
	- param <a href="../classes/Event.html" class="crosslink">Event</a> event - the input event




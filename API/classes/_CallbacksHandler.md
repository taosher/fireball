
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `_CallbacksHandler` Class


Defined in: [utils/api/core/callbacks-invoker.js:6](../files/utils/api/core/callbacks-invoker.js.js)

Module: [Fire](../modules/Fire.md)




The CallbacksHandler is an abstract class that can register and unregister callbacks by key.
Subclasses should implement their own methods about how to invoke the callbacks.

### Index



##### Methods

  - `_CallbacksHandler` **constructor**
  - `add`
  - `has`
  - `remove`
  - `removeAll`





### Details




<!-- Method Block -->
#### Methods

##### Constructor

##### method: `_CallbacksHandler()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/callbacks-invoker.js:6` |



##### method: `add()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/callbacks-invoker.js:19` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- key <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> can be null


##### method: `has()`

Check if the specified key has any registered callback. If a callback is also specified,
it will only return true if the callback is registered.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/callbacks-invoker.js:47` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- key <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  


##### method: `remove()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/callbacks-invoker.js:74` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- key <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  


##### method: `removeAll()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/callbacks-invoker.js:66` |

###### Parameters
- key <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  




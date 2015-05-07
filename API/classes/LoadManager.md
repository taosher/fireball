
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `LoadManager` Class


Defined in: [utils/api/engine/load-manager.js:5](../files/utils/api/engine/load-manager.js.js)

Module: [Fire](../modules/Fire.md)




The manager scheduling resources loading
- It will:
  - select registered loader
  - merge same url request
  - limit the max concurrent request
- It will NOT:
  - cache what has being loaded
  - load depends of resource

### Index

##### Properties

  - `_curConcurrent`
  - `maxConcurrent`



##### Methods

  - `load`
  - `loadByLoader`
  - `registerRawTypes`





### Details


#### Properties



##### property: `_curConcurrent`

Current concurrent request count

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/load-manager.js:77` |




##### property: `maxConcurrent`

Max allowed concurrent request count

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/load-manager.js:69` |
| Default    | 2 |






<!-- Method Block -->
#### Methods


##### method: `load()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/load-manager.js:111` |

###### Parameters
- url <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- rawType <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- rawExtname <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> error - null or the error info
	- param Any data - the loaded data


##### method: `loadByLoader()`

NOTE: Request the same url with different loader is disallowed

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/load-manager.js:85` |

###### Parameters
- loader <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
- url <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> error - null or the error info
	- param Any data - the loaded data


##### method: `registerRawTypes()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/load-manager.js:143` |

###### Parameters
- rawType <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- loader <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
- defaultExtname <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  




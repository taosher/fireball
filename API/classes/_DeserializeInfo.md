
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `_DeserializeInfo` Class


Defined in: [utils/api/core/deserialize.js:402](../files/utils/api/core/deserialize.js.js)

Module: [Fire](../modules/Fire.md)




 

### Index

##### Properties

  - `rawProp`
  - `uuidList`
  - `uuidObjList`
  - `uuidPropList`



##### Methods

  - `_DeserializeInfo` **constructor**
  - `assignAssetsBy`
  - `getUuidOf`
  - `reset`





### Details


#### Properties



##### property: `rawProp`

the corresponding field name which referenced to the raw object

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/core/deserialize.js:436` |




##### property: `uuidList`

list of the depends assets' uuid

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String[]</a> |
| Defined | `utils/api/core/deserialize.js:414` |




##### property: `uuidObjList`

the obj list whose field needs to load asset by uuid

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object[]</a> |
| Defined | `utils/api/core/deserialize.js:420` |




##### property: `uuidPropList`

the corresponding field name which referenced to the asset

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String[]</a> |
| Defined | `utils/api/core/deserialize.js:426` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `_DeserializeInfo()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/deserialize.js:402` |



##### method: `assignAssetsBy()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/deserialize.js:475` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- getter <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  


##### method: `getUuidOf()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/deserialize.js:460` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 

###### Parameters
- obj <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a>  
- propName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `reset()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/deserialize.js:448` |





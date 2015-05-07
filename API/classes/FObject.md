
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `FObject` Class


Defined in: [utils/api/core/object.js:4](../files/utils/api/core/object.js.js)

Module: [Fire](../modules/Fire.md)




The base class of most of all the objects in Fireball.

### Index

##### Properties

  - `_name`
  - `_objFlags`
  - `isValid`
  - `name`



##### Methods

  - `FObject` **constructor**
  - `_deserialize`
  - `_destruct`
  - `_onPreDestroy`
  - `_serialize`
  - `destroy`
  - `isValid`





### Details


#### Properties



##### property: `_name`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/core/object.js:15` |
| Default    | &quot;&quot; |




##### property: `_objFlags`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/object.js:23` |
| Default    | 0 |




##### property: `isValid`

Indicates whether the object is not yet destroyed

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/core/object.js:94` |
| Default    | true |




##### property: `name`

The name of the object.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined | `utils/api/core/object.js:79` |
| Default    | &quot;&quot; |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `FObject()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:4` |



##### method: `_deserialize()`

Init this object from the custom serialized data.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:203` |

###### Parameters
- data <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> the serialized json data
- ctx _Deserializer  
- target <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a>  


##### method: `_destruct()`

Clear all references in the instance.

NOTE: this method will not clear the getter or setter functions which defined in the INSTANCE of FObject.
      You can override the _destruct method if you need.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:139` |



##### method: `_onPreDestroy()`

Called before the object being destroyed.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:170` |



##### method: `_serialize()`

The customized serialization for this object. (Editor Only)

| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:193` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 

###### Parameters
- exporting <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a>  


##### method: `destroy()`

Destroy this FObject, and release all its own references to other resources.

After destory, this FObject is not usable any more.
You can use Fire.isValid(obj) (or obj.isValid if obj is non-nil) to check whether the object is destroyed before
accessing it.

| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:109` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 



##### method: `isValid()`

Checks whether the object is non-nil and not yet destroyed

| meta | description |
|------|-------------|
| Defined | `utils/api/core/object.js:219` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- object <a href="../classes/FObject.html" class="crosslink">FObject</a>  




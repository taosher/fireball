
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Entity` Class


Defined in: [utils/api/engine/entity.js:4](../files/utils/api/engine/entity.js.js)

Module: [Fire](../modules/Fire.md)




Class of all entities in scenes.

### Index

##### Properties

  - `_children`
  - `_components`
  - `_defaultFlags`
  - `active`
  - `activeInHierarchy`
  - `childCount`
  - `dontDestroyOnLoad`
  - `parent`
  - `transform`



##### Methods

  - `Entity` **constructor**
  - `addComponent`
  - `animate`
  - `find`
  - `find`
  - `getChild`
  - `getChildren`
  - `getComponent`
  - `getSibling`
  - `getSiblingIndex`
  - `hitTest`
  - `isChildOf`
  - `setAsFirstSibling`
  - `setAsLastSibling`
  - `setSiblingIndex`





### Details


#### Properties



##### property: `_children`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Entity.html" class="crosslink">Entity[]</a> |
| Defined | `utils/api/engine/entity.js:219` |
| Default    | [] |




##### property: `_components`



| meta | description |
|------|-------------|
| Type | <a href="../classes/Component.html" class="crosslink">Component[]</a> |
| Defined | `utils/api/engine/entity.js:228` |
| Default    | [] |




##### property: `_defaultFlags`

The temp property that indicates the current creating entity should
binded with supplied object flags. This property only used in editor.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/entity.js:773` |
| Default    | 0 |




##### property: `active`

The local active state of this Entity.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/entity.js:76` |
| Default    | true |




##### property: `activeInHierarchy`

Indicates whether this entity is active in the scene.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/entity.js:99` |




##### property: `childCount`

Get the amount of children

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/entity.js:182` |




##### property: `dontDestroyOnLoad`

If true, the entity will not be destroyed automatically when loading a new scene.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/entity.js:194` |
| Default    | false |




##### property: `parent`

The parent of the entity.
Changing the parent will keep the transform's local space position, rotation and scale the same but modify
the world space position, scale and rotation.

| meta | description |
|------|-------------|
| Type | <a href="../classes/Entity.html" class="crosslink">Entity</a> |
| Defined | `utils/api/engine/entity.js:121` |
| Default    | null |




##### property: `transform`

Returns the {% crosslink Fire.Transform Transform %} attached to the entity.

| meta | description |
|------|-------------|
| Type | <a href="../classes/Transform.html" class="crosslink">Transform</a> |
| Defined | `utils/api/engine/entity.js:110` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Entity()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:4` |

###### Parameters
- name <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the name of the entity


##### method: `addComponent()`

Adds a component class to the entity. You can also add component to entity by passing in the name of the script.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:320` |
| Return 		 | <a href="../classes/Component.html" class="crosslink">Component</a> 

###### Parameters
- typeOrName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the constructor or the class name of the component to add


##### method: `animate()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:655` |
| Return 		 | <a href="../classes/AnimationNode.html" class="crosslink">AnimationNode</a> 

###### Parameters
- keyFrames <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object[]</a>  
- timingInput <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> This dictionary is used as a convenience for specifying the timing properties of
                              an Animation in bulk.


##### method: `find()`

Finds an entity by name in all children of this entity. This function will still returns the entity even if it
is inactive. It is recommended to not use this function every frame instead cache the result at startup.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:427` |
| Return 		 | <a href="../classes/Entity.html" class="crosslink">Entity</a> 

###### Parameters
- path <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `find()`

Finds an entity by hierarchy path, the path is case-sensitive, and must start with a '/' character.
It will traverse the hierarchy by splitting the path using '/' character.
It is recommended to not use this function every frame instead cache the result at startup.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:785` |
| Return 		 | <a href="../classes/Entity.html" class="crosslink">Entity</a> 

###### Parameters
- path <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `getChild()`

Returns an entity child by index.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:479` |
| Return 		 | <a href="../classes/Entity.html" class="crosslink">Entity</a> 

###### Parameters
- index <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `getChildren()`

Returns a new arrays of all children.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:490` |
| Return 		 | <a href="../classes/Entity.html" class="crosslink">Entity[]</a> 



##### method: `getComponent()`

Returns the component of supplied type if the entity has one attached, null if it doesn't. You can also get
component in the entity by passing in the name of the script.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:369` |
| Return 		 | <a href="../classes/Component.html" class="crosslink">Component</a> 

###### Parameters
- typeOrName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `getSibling()`

Get the indexed sibling.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:537` |
| Return 		 | <a href="../classes/Entity.html" class="crosslink">Entity</a> 

###### Parameters
- index <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  


##### method: `getSiblingIndex()`

Get the sibling index.

NOTE: If this entity does not have parent and not belongs to the current scene,
      The return value will be -1

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:519` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 



##### method: `hitTest()`

Tests whether the entity intersects the specified point in world coordinates
This ignores the alpha of the renderer.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:603` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- worldX <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> The world X position to check.
- worldY <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> The world Y position to check.


##### method: `isChildOf()`

Is this entity a child of the parent?

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:500` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- parent <a href="../classes/Entity.html" class="crosslink">Entity</a>  


##### method: `setAsFirstSibling()`

Move the entity to the top.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:581` |



##### method: `setAsLastSibling()`

Move the entity to the bottom.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:590` |



##### method: `setSiblingIndex()`

Set the sibling index of this entity.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/entity.js:553` |

###### Parameters
- index <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  




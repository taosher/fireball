
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Component` Class

Extends `HashObject`

Defined in: [utils/api/engine/component.js:26](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Base class for everything attached to Entity.

NOTE: Not allowed to use construction parameters for Component's subclasses,
        because Component is created by the engine.

### Index

##### Properties

  - `_enabled`
  - `enabled`
  - `enabledInHierarchy`
  - `entity`
  - `isOnLoadCalled`
  - `transform`



##### Methods

  - `Component` **constructor**
  - `addComponent`
  - `addComponentMenu`
  - `executeInEditMode`
  - `getComponent`



##### Events

  - `lateUpdate`
  - `onDestroy`
  - `onDisable`
  - `onEnable`
  - `onLoad`
  - `onPreRender`
  - `start`
  - `update`



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




### Inheritance tree


### Details


#### Properties



##### property: `_enabled`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/component.js:76` |




##### property: `enabled`

indicates whether this component is enabled or not.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/component.js:85` |
| Default    | true |




##### property: `enabledInHierarchy`

indicates whether this component is enabled and its entity is also active in the hierarchy.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/component.js:107` |




##### property: `entity`

The entity this component is attached to. A component is always attached to an entity.

| meta | description |
|------|-------------|
| Type | <a href="../classes/Entity.html" class="crosslink">Entity</a> |
| Defined | `utils/api/engine/component.js:38` |




##### property: `isOnLoadCalled`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/component.js:131` |




##### property: `transform`

Returns the {% crosslink Fire.Transform Transform %} attached to the entity.

| meta | description |
|------|-------------|
| Type | <a href="../classes/Transform.html" class="crosslink">Transform</a> |
| Defined | `utils/api/engine/component.js:119` |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `Component()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/component.js:26` |



##### method: `addComponent()`

Adds a component class to the entity. You can also add component to entity by passing in the name of the script.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/component.js:192` |
| Return 		 | <a href="../classes/Component.html" class="crosslink">Component</a> 

###### Parameters
- typeOrName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the constructor or the class name of the component to add


##### method: `addComponentMenu()`

Register a component to the "Component" menu.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/component.js:417` |

###### Parameters
- constructor <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> the class you want to register, must inherit from Component
- menuPath <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the menu path name. Eg. "Rendering/Camera"
- priority <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> the order which the menu item are displayed


##### method: `executeInEditMode()`

Makes a component execute in edit mode.
By default, all components are only executed in play mode,
which means they will not have their callback functions executed while the Editor is in edit mode.
By calling this function, each component will also have its callback executed in edit mode.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/component.js:443` |

###### Parameters
- constructor <a href="../classes/Component.html" class="crosslink">Component</a> The class you want to register, must inherit from Component.
- live <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> If true, the scene view will keep updating this entity in 60 fps when it is selected,
                        otherwise, it will update only if necessary.


##### method: `getComponent()`

Returns the component of supplied type if the entity has one attached, null if it doesn't. You can also get
component in the entity by passing in the name of the script.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/component.js:203` |
| Return 		 | <a href="../classes/Component.html" class="crosslink">Component</a> 

###### Parameters
- typeOrName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  




#### Events

### `lateUpdate` Event


Defined in: [utils/api/engine/component.js:148](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




LateUpdate is called every frame, if the Component is enabled.

### Index







### Details




### `onDestroy` Event


Defined in: [utils/api/engine/component.js:179](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Called when this component will be destroyed.

### Index







### Details




### `onDisable` Event


Defined in: [utils/api/engine/component.js:173](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Called when this component becomes disabled or its entity becomes inactive

### Index







### Details




### `onEnable` Event


Defined in: [utils/api/engine/component.js:167](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Called when this component becomes enabled and its entity becomes active

### Index







### Details




### `onLoad` Event


Defined in: [utils/api/engine/component.js:155](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




When attaching to an active entity or its entity first activated

### Index







### Details




### `onPreRender` Event


Defined in: [utils/api/engine/component.js:185](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Called when the engine starts rendering the scene.

### Index







### Details




### `start` Event


Defined in: [utils/api/engine/component.js:161](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Called before all scripts' update if the Component is enabled

### Index







### Details




### `update` Event


Defined in: [utils/api/engine/component.js:142](../files/utils/api/engine/component.js.js)

Module: [Fire](../modules/Fire.md)




Update is called every frame, if the Component is enabled.

### Index







### Details






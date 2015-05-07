
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `_ObjectFlags` Class


Defined in: [utils/api/core/definition.js:126](../files/utils/api/core/definition.js.js)

Module: [Fire](../modules/Fire.md)




Bit mask that controls object states.

### Index

##### Properties

  - `DontDestroy`
  - `DontSave`
  - `EditorOnly`
  - `Hide`
  - `HideInEditor`
  - `HideInGame`







### Details


#### Properties



##### property: `DontDestroy`

Dont destroy automatically when loading a new scene.

| meta | description |
|------|-------------|
| Type | Unknown |
| Defined | `utils/api/core/definition.js:152` |




##### property: `DontSave`

The object will not be saved.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/definition.js:136` |




##### property: `EditorOnly`

The object will not be saved when building a player.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/definition.js:143` |




##### property: `Hide`

Hide in game view, hierarchy, and scene view... etc.
This flag is readonly, it can only be used as an argument of scene.addEntity() or Entity.createWithFlags()

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/definition.js:188` |




##### property: `HideInEditor`

This flag is readonly, it can only be used as an argument of scene.addEntity() or Entity.createWithFlags()

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/definition.js:173` |




##### property: `HideInGame`

Hide in game and hierarchy.
This flag is readonly, it can only be used as an argument of scene.addEntity() or Entity.createWithFlags()

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/core/definition.js:163` |







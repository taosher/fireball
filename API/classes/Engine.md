
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Engine` Class

Extends `Playable`

Defined in: [utils/api/engine/engine.js:7](../files/utils/api/engine/engine.js.js)

Module: [Fire](../modules/Fire.md)





 Access to engine runtime data.
This class contains static methods for looking up information about and controlling the runtime data.

### Index

##### Properties

  - `_animationManager`
  - `_canModifyCurrentScene`
  - `_curRenderContext`
  - `_inputContext`
  - `_interactionContext`
  - `_renderContext`
  - `_scene`
  - `inited`
  - `isLoadingScene`
  - `isPaused`
  - `isPlaying`



##### Methods

  - `_launchScene`
  - `_loadSceneByUuid`
  - `init`
  - `loadScene`
  - `pause`
  - `play`
  - `preloadScene`
  - `step`
  - `stop`
  - `update`




### Inherited members

##### Properties

- `isUpdating`

##### Attributes


##### Methods

- `onPlay
- `onPause
- `onResume
- `onStop
- `onError

##### Events




### Details


#### Properties



##### property: `_animationManager`

The instance of global AnimationManager.

| meta | description |
|------|-------------|
| Type | AnimationManager |
| Defined | `utils/api/engine/engine.js:82` |




##### property: `_canModifyCurrentScene`


 You should check whether you can modify the scene in constructors which may called by the engine while
deserializing.


| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/engine.js:102` |




##### property: `_curRenderContext`

the render context currently rendering

| meta | description |
|------|-------------|
| Type | <a href="../classes/_Runtime.RenderContext.html" class="crosslink">_Runtime.RenderContext</a> |
| Defined | `utils/api/engine/engine.js:66` |




##### property: `_inputContext`

The InputContext attached to game or game view.

| meta | description |
|------|-------------|
| Type | InputContext |
| Defined | `utils/api/engine/engine.js:74` |




##### property: `_interactionContext`

The InteractionContext attached to game or game view.

| meta | description |
|------|-------------|
| Type | InteractionContext |
| Defined | `utils/api/engine/engine.js:58` |




##### property: `_renderContext`

The RenderContext attached to game or game view.

| meta | description |
|------|-------------|
| Type | <a href="../classes/_Runtime.RenderContext.html" class="crosslink">_Runtime.RenderContext</a> |
| Defined | `utils/api/engine/engine.js:50` |




##### property: `_scene`


 the active scene


| meta | description |
|------|-------------|
| Type | Scene |
| Defined | `utils/api/engine/engine.js:30` |




##### property: `inited`



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/engine.js:134` |




##### property: `isLoadingScene`

is loading scene?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined | `utils/api/engine/engine.js:90` |




##### property: `isPaused`

is editor currently paused?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Overwritten | inherited from Playable but overwritten in `utils/api/engine/engine.js:441` |
| Defined | `utils/api/engine/engine.js:441` |




##### property: `isPlaying`

is in player or playing in editor?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Overwritten | inherited from Playable but overwritten in `utils/api/engine/engine.js:435` |
| Defined | `utils/api/engine/engine.js:435` |






<!-- Method Block -->
#### Methods


##### method: `_launchScene()`

Launch loaded scene.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/engine.js:287` |

###### Parameters
- scene Scene  
- onBeforeLoadScene <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  


##### method: `_loadSceneByUuid()`

Loads the scene by its uuid.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/engine.js:371` |

###### Parameters
- uuid <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the uuid of the scene asset to load
- onLaunched <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
- onUnloaded <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  


##### method: `init()`

Initialize the engine. This method will be called by boot.js or editor.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/engine.js:148` |
| Return 		 | <a href="../classes/_Runtime.RenderContext.html" class="crosslink">_Runtime.RenderContext</a> 

###### Parameters
- width <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- height <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a>  
- canvas Canvas  
- options <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a>  


##### method: `loadScene()`

Loads the scene by its name.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/engine.js:346` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- sceneName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the name of the scene to load
- onLaunched <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> callback, will be called after scene launched
- onUnloaded <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> callback, will be called when the previous scene was unloaded


##### method: `pause()`

Pause the engine loop.

| meta | description |
|------|-------------|
| Overwritten | inherited from Playable but overwritten in `utils/api/engine/engine.js:455` |
| Defined | `utils/api/engine/engine.js:455` |



##### method: `play()`

Start the engine loop. This method will be called by boot.js or editor.

| meta | description |
|------|-------------|
| Overwritten | inherited from Playable but overwritten in `utils/api/engine/engine.js:447` |
| Defined | `utils/api/engine/engine.js:447` |



##### method: `preloadScene()`

Preloads the scene to reduces loading time. You can call this method at any time you want.

After calling this method, you still need to launch the scene by `Engine.loadScene` because the loading logic
will not changed. It will be totally fine to call `Engine.loadScene` at any time even if the preloading is not
yet finished, the scene will be launched after loaded automatically.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/engine.js:405` |

###### Parameters
- sceneName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> the name of the scene to preload
- onLoaded <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> callback, will be called after the scene loaded
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> error - null or the error info
	- param <a href="../classes/Asset.html" class="crosslink">Asset</a> data - the loaded scene or null


##### method: `step()`

Perform a single frame step.

| meta | description |
|------|-------------|
| Overwritten | inherited from Playable but overwritten in `utils/api/engine/engine.js:459` |
| Defined | `utils/api/engine/engine.js:459` |



##### method: `stop()`

Stop the engine loop.

| meta | description |
|------|-------------|
| Overwritten | inherited from Playable but overwritten in `utils/api/engine/engine.js:451` |
| Defined | `utils/api/engine/engine.js:451` |



##### method: `update()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/engine.js:259` |





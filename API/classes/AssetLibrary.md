
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `AssetLibrary` Class


Defined in: [utils/api/engine/asset-library.js:4](../files/utils/api/engine/asset-library.js.js)

Module: [Fire](../modules/Fire.md)




The asset library which managing loading/unloading assets in project.

### Index

##### Properties

  - `_uuidToAsset`



##### Methods

  - `_deserializeWithDepends`
  - `_loadAssetByUuid`
  - `getAssetByUuid`
  - `init`
  - `loadAsset`
  - `loadJson`
  - `unloadAsset`





### Details


#### Properties



##### property: `_uuidToAsset`


 Caches uuid to all loaded assets in scenes.



| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined | `utils/api/engine/asset-library.js:375` |






<!-- Method Block -->
#### Methods


##### method: `_deserializeWithDepends()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:168` |

###### Parameters
- json <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a>  
- url <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> error - null or the error info
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> data - the loaded object or null
- handle <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> the loading context which reserves all relevant parameters
- existingAsset <a href="../classes/Asset.html" class="crosslink">Asset</a> existing asset to reload


##### method: `_loadAssetByUuid()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:82` |

###### Parameters
- uuid <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback AssetLibrary~loadCallback the callback to receive the asset, can be null
- handle LoadingHandle the loading context which reserves all relevant parameters
- existingAsset <a href="../classes/Asset.html" class="crosslink">Asset</a> load to existing asset, this argument is only available in editor


##### method: `getAssetByUuid()`

Get the exists asset by uuid.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:303` |
| Return 		 | <a href="../classes/Asset.html" class="crosslink">Asset</a> 

###### Parameters
- uuid <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `init()`

init the asset library

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:350` |

###### Parameters
- libraryPath <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `loadAsset()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:63` |

###### Parameters
- uuid <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- callback LoadCallback  
- readMainCache <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> If false, the asset and all its depends assets will reload and create new instances from library.
- writeMainCache <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> If true, the result will cache to AssetLibrary, and MUST be unload by user manually.
- existingAsset <a href="../classes/Asset.html" class="crosslink">Asset</a> load to existing asset, this argument is only available in editor


##### method: `loadJson()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:154` |

###### Parameters
- json <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a>  
- callback <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a>  
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> error - null or the error info
	- param <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> data - the loaded object or null
- dontCache <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> If false, the result will cache to AssetLibrary, and MUST be unload by user manually.


##### method: `unloadAsset()`


 Kill references to the asset so it can be garbage collected.
Fireball will reload the asset from disk or remote if loadAssetByUuid being called again.
You rarely use this function in scripts, since it will be called automatically when the Asset is destroyed.


| meta | description |
|------|-------------|
| Defined | `utils/api/engine/asset-library.js:321` |

###### Parameters
- assetOrUuid <a href="../classes/Asset.html" class="crosslink">Asset</a> | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- destroy <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> When destroyImmediate is true, if there are objects referencing the asset,
                                   the references will become invalid.




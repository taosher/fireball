
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `SkeletonRenderer` Class

Extends `Renderer`

Defined in: [utils/api/engine/skeleton-renderer.js:11](../files/utils/api/engine/skeleton-renderer.js.js)

Module: [Fire.Spine](../modules/Fire.Spine.md)




 

### Index

##### Properties

  - `skeletonData`
  - `timeScale`



##### Methods

  - `SkeletonRenderer` **constructor**
  - `findBone`
  - `findSlot`
  - `getAttachment`
  - `setAttachment`
  - `setBonesToSetupPose`
  - `setSkin`
  - `setSlotsToSetupPose`




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

- `getWorldBounds
- `getWorldOrientedBounds
- `getSelfMatrix
- `getWorldSize
- `onPreRender
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



##### property: `skeletonData`



| meta | description |
|------|-------------|
| Type | <a href="../classes/SkeletonDataAsset.html" class="crosslink">SkeletonDataAsset</a> |
| Defined | `utils/api/engine/skeleton-renderer.js:27` |




##### property: `timeScale`

The time scale of this skeleton.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined | `utils/api/engine/skeleton-renderer.js:86` |
| Default    | 1 |






<!-- Method Block -->
#### Methods

##### Constructor

##### method: `SkeletonRenderer()`



| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:11` |



##### method: `findBone()`

Finds a bone by name. This does a string comparison for every bone.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:147` |
| Return 		 | spine.Bone 

###### Parameters
- boneName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `findSlot()`

Finds a slot by name. This does a string comparison for every slot.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:158` |
| Return 		 | spine.Slot 

###### Parameters
- slotName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `getAttachment()`

Returns the attachment for the slot and attachment name. The skeleton looks first in its skin, then in the
skeleton data’s default skin.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:181` |
| Return 		 | spine.RegionAttachment | spine.BoundingBoxAttachment 

###### Parameters
- slotName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- attachmentName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `setAttachment()`

Sets the attachment for the slot and attachment name. The skeleton looks first in its skin, then in the
skeleton data’s default skin.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:194` |

###### Parameters
- slotName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  
- attachmentName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `setBonesToSetupPose()`

Sets the bones to the setup pose, using the values from the `BoneData` list in the `SkeletonData`.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:129` |



##### method: `setSkin()`

Finds a skin by name and makes it the active skin. This does a string comparison for every skin. Note that
setting the skin does not change which attachments are visible.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:169` |
| Return 		 | spine.Skin 

###### Parameters
- skinName <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a>  


##### method: `setSlotsToSetupPose()`

Sets the slots to the setup pose, using the values from the `SlotData` list in the `SkeletonData`.

| meta | description |
|------|-------------|
| Defined | `utils/api/engine/skeleton-renderer.js:138` |





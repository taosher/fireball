
# fireball-build 0.3.0

Fireball is the game engine for the future.

### `Intersection` Class


Defined in: [utils/api/core/intersection.js:4](../files/utils/api/core/intersection.js.js)

Module: [Fire](../modules/Fire.md)




 

### Index



##### Methods

  - `lineLine`
  - `linePolygon`
  - `lineRect`
  - `polygonPolygon`
  - `rectPolygon`
  - `rectRect`





### Details




<!-- Method Block -->
#### Methods


##### method: `lineLine()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/intersection.js:11` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- a1 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- a2 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- b1 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- b2 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `linePolygon()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/intersection.js:70` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- a1 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- a2 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- b Polygon  


##### method: `lineRect()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/intersection.js:40` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- a1 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- a2 <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  
- b <a href="../classes/Vec2.html" class="crosslink">Vec2</a>  


##### method: `polygonPolygon()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/intersection.js:166` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- a Polygon  
- b Polygon  


##### method: `rectPolygon()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/intersection.js:117` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- a <a href="../classes/Rect.html" class="crosslink">Rect</a>  
- b Polygon  


##### method: `rectRect()`



| meta | description |
|------|-------------|
| Defined | `utils/api/core/intersection.js:92` |
| Return 		 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 

###### Parameters
- a <a href="../classes/Rect.html" class="crosslink">Rect</a>  
- b <a href="../classes/Rect.html" class="crosslink">Rect</a>  




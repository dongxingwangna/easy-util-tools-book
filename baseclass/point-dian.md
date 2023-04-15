---
description: Used to represent a two-dimensional coordinate point or vector
---

# 😃 Point(点)

```javascript
// Import the class
import { Point } from 'easy-util-tools'

//The Instantiate Class parameter is a two-dimensional coordinate  x, y
let point = new Point(0, 0)
```

```javascript
/**
* 获取到点的距离
* Gets the distance to the point
* @param point
*/
 let distance=point.getDistanceToPoint(point:Point);
```

```typescript
/**
 *  判断点是否在当前这个点的范围内
 *  Determine whether the point is within the range of the current point
 * @param point
 * @param radius
 * @param type
 */
 let inArea = point.isPointInArea(point:Point, radius:number, type:'round'|'square');
```

```typescript
/**
* 获取到线的距离
* Gets the distance to the line
* @param line
*/
let distance = point.getDistanceToLine(line:Line);
```

```typescript
/**
* 获取距离最近的点
* Gets the point closest to the distance
* @param points
*/
let info = point.getClosestPoint(points:Point[])
```

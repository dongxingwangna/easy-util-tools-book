---
description: A line or segment represented by two points
---

# Line(线)

```typescript
// Import the class
import { Line } from 'easy-util-tools'

/**
* 第一个参数表示线的起始点，第二个参数表示线的结束点，第三个参数表示线长度是否有限，如果长度有限则代表是一条线段，否则是直线
* The first parameter indicates the start point of the line, the second parameter indicates the end point of the line, and the third parameter indicates whether the line length is finite, if the length is finite, it represents a line segment, otherwise it is a straight line
*/
let line = new Line(point, point, limited);
```

```typescript
/**
* 获取与x轴的夹角
* Gets the angle to the x-axis
* @param isDirection
*/
let angle = line.getXAxisAngle(isDirection);
```


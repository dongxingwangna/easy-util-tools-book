# Circle(圆)

```typescript
// Import the class
import { Line } from 'easy-util-tools'

let circle = new Circle(center:Point, radius:number);
```

```typescript
/**
 * 获取圆上的点
 * Gets the point on the circle
 * @param angle 点所在的角度 The angle at which the point is located
 * @param startDirection 起始方向 Start direction
 * @param clockwiseOrNot 是否为顺时针 Whether it is clockwise
 */
 let point = circle.getPointOnCircle(
    angle: number,
    startDirection: 'top' | 'right' | 'bottom' | 'left' = 'right',
    clockwiseOrNot: boolean = false,
  )
```

# Circle(圆)

```typescript
// Import the class
import { Line } from 'easy-util-tools'

/**
 * 创建圆实例
 * Create a circle instance
 * @param center type Point
 * @param radius type number
 */
let circle = new Circle(center, radius);
```

```typescript
/**
 * 获取圆上的点
 * Gets the point on the circle
 * @param angle 点所在的角度 The angle at which the point is located
 * @param startDirection 起始方向 Start direction 'top' | 'right' | 'bottom' | 'left' defalute right
 * @param clockwiseOrNot 是否为顺时针 Whether it is clockwise
 */
 let point = circle.getPointOnCircle(
    45,
    'right',
    false,
  )
```

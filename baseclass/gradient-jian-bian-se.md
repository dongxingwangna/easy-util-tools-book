---
description: >-
  This class can implement a custom color spectrum, and then obtain the color
  return value type at any point on the color spectrum is Color, please refer to
  the Color class for details
---

# Gradient(渐变色)

```typescript
// Import the module
import { Gradient } from 'easy-util-tools'

// The Instantiate Class parameter is an array of Color class instances
let gradient = new Gradient([
    new Color(0, 0, 0),
    new Color(255, 255, 255)
])

// Get color values The value interval of the Get Color Value parameter is a decimal number between 0-1
let color = grandient.getColor(v)

//exampleResetsChromatography
gradient.chromatogram = Color[]
```

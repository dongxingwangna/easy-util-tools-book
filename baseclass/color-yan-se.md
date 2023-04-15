---
description: This class can be used to convert color values
---

# Color(颜色)

```typescript
// Import the module
import { Color } from 'easy-util-tools'
```

```typescript
//Instantiate the class
let color = new Color(255, 0, 0)
```

```typescript
/**
 * 通道颜色，这个属性新增于1.0.3版本，这个属性只读
 * Channel color, this property was added in version 1.0.3, this property is read-only
 */
let channel = color.channel;
```

```typescript
/**
* 十六进制颜色值，这个属性新增于1.0.3版本，这个属性只读
* Hexadecimal color value, this property was added in version 1.0.3, this property is read-only
*/
let hex = color.hex;
```

```typescript
/**
* rgb颜色，这个属性新增于1.0.3版本，这个属性只读
* rgb color, this attribute has been added in version 1.0.3, this property is read-only
*/
let rgb = color.rgb
```

```typescript
/**
* 获取通道颜色 此方法已于1.0.8版本废弃，可以直接使用channel属性获取
* Get channel color This method will be deprecated in the next minor version and can be obtained directly using the channel property
*/
let channelColor = color.getChannelColor()
```

```typescript
/**
* 获取十六进制颜色值 此方法已于1.0.8版本废弃，可以直接使用hex属性获取
* Get hexadecimal color value This method will be deprecated in the next minor version and can be obtained directly using the hex property
*/
let hexColor = color.getHexColor()
```

```typescript
/**
* 获取rgb颜色 此方法已于1.0.8版本废弃，可以直接使用rgb属性获取
* Get RGB color This method will be deprecated in the next minor version and can be obtained directly using the rgb property
*/
let rgbColor = color.getRgbColor()
```

```typescript
//Read a hexadecimal color value to an instance The argument can be hexadecimal or a hexadecimal string 'ffffff' or '0xffffff'
color.readHexColor('#ffffff')
```

```typescript
// Read RGB value to instance parameter is r g The size of the value is 0-255
color.readRgbColor(0, 0, 0)
```

```typescript
// Read the channel color to the instance parameter is r g b and takes values 0-1
color.readChannelColor(0, 0, 0)
```

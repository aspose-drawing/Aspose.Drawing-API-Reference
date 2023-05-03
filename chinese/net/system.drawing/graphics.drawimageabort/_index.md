---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing for .NET API 参考
description: 提供一个回调方法来决定何时DrawImage./graphics/drawimage方法应该提前取消执行并停止绘制图像
type: docs
weight: 540
url: /zh/net/system.drawing/graphics.drawimageabort/
---
## Graphics.DrawImageAbort delegate

提供一个回调方法来决定何时[`DrawImage`](../graphics/drawimage)方法应该提前取消执行并停止绘制图像。

```csharp
public delegate bool DrawImageAbort(IntPtr callbackdata);
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callbackdata | IntPtr | 为回调方法指定数据的内部指针。这个参数不是所有人都传的[`DrawImage`](../graphics/drawimage)过载。您可以通过检查值来测试它是否存在Zero. |

### 返回值

如果该方法确定[`DrawImage`](../graphics/drawimage)方法应该过早停止执行。否则返回 false 表示[`DrawImage`](../graphics/drawimage)方法应该继续执行。

### 也可以看看

* class [Graphics](../graphics)
* 命名空间 [System.Drawing](../../system.drawing)
* 部件 [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
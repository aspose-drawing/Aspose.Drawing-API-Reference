---
title: ImageLockMode
second_title: Aspose.Drawing for Java API संदर्भ
description: फ़्लैग्स को निर्दिष्ट करता है जो मेथड के flags पैरामीटर को पास किए जाते हैं।
type: docs
weight: 28
url: /hi/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

फ़्लैग्स को निर्दिष्ट करता है जो [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) मेथड के flags पैरामीटर को पास किए जाते हैं। [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) मेथड एक छवि के हिस्से को लॉक करता है ताकि आप पिक्सेल डेटा को पढ़ या लिख सकें।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ReadOnly](#ReadOnly) | निर्दिष्ट करता है कि छवि का एक भाग पढ़ने के लिए लॉक किया गया है। |
| [WriteOnly](#WriteOnly) | निर्दिष्ट करता है कि छवि का एक भाग लिखने के लिए लॉक किया गया है। |
| [ReadWrite](#ReadWrite) | निर्दिष्ट करता है कि छवि का एक भाग पढ़ने या लिखने के लिए लॉक किया गया है। |
| [UserInputBuffer](#UserInputBuffer) | निर्दिष्ट करता है कि पिक्सेल डेटा को पढ़ने या लिखने के लिए उपयोग किया जाने वाला बफ़र उपयोगकर्ता द्वारा आवंटित किया गया है। |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


निर्दिष्ट करता है कि छवि का एक भाग पढ़ने के लिए लॉक किया गया है।

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


निर्दिष्ट करता है कि छवि का एक भाग लिखने के लिए लॉक किया गया है।

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


निर्दिष्ट करता है कि छवि का एक भाग पढ़ने या लिखने के लिए लॉक किया गया है।

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


निर्दिष्ट करता है कि पिक्सेल डेटा को पढ़ने या लिखने के लिए उपयोग किया जाने वाला बफ़र उपयोगकर्ता द्वारा आवंटित किया गया है। यदि यह फ़्लैग सेट किया गया है, तो [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) मेथड का `flags` पैरामीटर इनपुट पैरामीटर के रूप में कार्य करता है (और संभवतः आउटपुट पैरामीटर के रूप में भी)। यदि यह फ़्लैग साफ़ किया जाता है, तो `flags` पैरामीटर केवल आउटपुट पैरामीटर के रूप में कार्य करता है।


---
gallery_01:
  - url: /images/avatar.jpg
    image_path: /images/avatar.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /images/avatar.jpg
    image_path: /images/avatar.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /images/avatar.jpg
    image_path: /images/avatar.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"

gallery_02:
  - url: https://flic.kr/p/8a6Ven
    image_path: https://farm2.staticflickr.com/1272/4697500467_8294dac099_q.jpg
    alt: "Black and grays with a hint of green"
  - url: https://flic.kr/p/8a738X
    image_path: https://farm5.staticflickr.com/4029/4697523701_249e93ba23_q.jpg
    alt: "Made for open text placement"
  - url: https://flic.kr/p/8a6VXP
    image_path: https://farm5.staticflickr.com/4046/4697502929_72c612c636_q.jpg
    alt: "Fog in the trees"
---


```python
# This is a python script

import numpy as np
import proplot as pplt

for i in range(12):
    print(i)

def CalcSum(a, b):
    c = a + b
    return c
```

> This is a sentence.
> This is a sentence.
> This is a text. This is a text. This is a sentence. This is a sentence. This is a sentence. This is a sentence. This is a sentence. This is a sentence. This is a sentence. This is a sentence. This is a sentence. This is a sentence.

> 这是一段引用的中文文本。

# 中文标题一
## 中文标题二
## 中文标题三
### 中文标题四
### 中文标题五
## 中文标题六


{% include gallery id="gallery_01" caption="This is a sample gallery with **Markdown support**." %}

{% include gallery id="gallery_02" caption="This is a second gallery example with images hosted externally." %}

{% include gallery id="gallery_01" class="full" caption="This is a third gallery example with two images and fills the entire content container." %}

{% include gallery id="gallery_01" layout="half" caption="This is a half gallery layout example." %}






















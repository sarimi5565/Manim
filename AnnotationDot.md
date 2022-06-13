# AnnotationDot
Dot yang lebih besar, ada isi berwarna, dan ada garis tepi

## Parameter
- **radius** = saiz dot (default = 1.3)
- **stroke_color** = warna garis tepi dot (default = WHITE)
- **fill_color** = warna isi dot (default = BLUE)
- **stroke_width** = saiz garis tepu (default = 5)

```python
from manim import *

class AnnotationDotExample(Scene):
    def construct(self):

        anno1 = AnnotationDot()
        anno2 = AnnotationDot(radius=2, stroke_color=RED, fill_color=YELLOW, stroke_width=10).next_to(anno1,RIGHT)

        self.add(anno1, anno2)
```
![AnnotationDot](image/AnnotationDotExample_ManimCE_v0.15.2.png)

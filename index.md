# Cara Penggunaan Manim Community Edition (ManimCE)

# Senarai Contoh

## Dot
```
from manim import *

class DotExample(Scene):
    def construct(self):
        # parameter point utk koordinate Dot (array)
        # parameter radius untuk saiz Dot (default = 0.08)
        dot1 = Dot(point=(-2,0,0), radius=0.1)
        # color untuk warna dot
        dot2 = Dot(point=ORIGIN, radius = 0.2, color=RED)
        dot3 = Dot(point=RIGHT)
        self.add(dot1,dot2,dot3)
```
![Contoh Dot](image/DotExample_ManimCE_v0.15.2.png)

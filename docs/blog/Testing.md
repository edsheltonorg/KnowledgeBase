---
# draft: true
title: Testing # URL
description: Test
authors:
  - ed
date:
  created: 2023-09-01
# readtime: 15
---

# Thing

Code:

```python
def thingee:
  x = 1 + 1
  y = print(x)
```

<!-- more -->

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/J---aiyznGQ?si=nDdW4i3CTo9yDD-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

!!! example 2

    === "C"

        ``` c
        #include <stdio.h>

        int main(void) {
          printf("Hello world!\n");
          return 0;
        }
        ```

    === "C++"

        ``` c++
        #include <iostream>

        int main(void) {
          std::cout << "Hello world!" << std::endl;
          return 0;
        }
        ```

Now check how they're linked below:

!!! example

    === "C"

        ``` c
        #include <stdio.h>

        int main(void) {
          printf("Hello world!\n");
          return 0;
        }
        ```

    === "C++"

        ``` c++
        #include <iostream>

        int main(void) {
          std::cout << "Hello world!" << std::endl;
          return 0;
        }
        ```
# C-Arraysize

A simple header file to determine the size of an array in c.

## Usage

To find out the size of an array just call `arraysize(<array>)`and pass an array to the function.

### Usage example

```c
#include "arraysize.h"
#include <stdio.h>

int main() {
    int arr[5] = {1, 2, 3, 4, 5};
    printf("%i", arraysize(arr));
    return 0;
}
```

The above example outputs the length of the array in the console.

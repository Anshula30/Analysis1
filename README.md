# Analysis

## Peer Assingment 1

```{r engine='Rcpp'}
#include <Rcpp.h>

int fibonacci(const int x) {
    if (x == 0 || x == 1) return(x);
    return (fibonacci(x - 1)) + fibonacci(x - 2);
}
```

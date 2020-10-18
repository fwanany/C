```c
#include <stdio.h>

int main(void){
    int c;
    printf("Please enter:");
    if(c = getchar() != EOF)
        printf("%d\n", c);
    
    return 0;
}
```


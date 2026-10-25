#include <stdio.h>

int main() 
{
    int i = 1;

    print_number:
    printf("%d\n", i);
    i++;

    if (i <= 5) {
        goto print_number
    }

    printf("Loop end!\n");
    return 0;
}

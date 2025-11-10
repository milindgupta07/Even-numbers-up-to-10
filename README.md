# Even-numbers-up-to-10
Using C language program is made which gives the output of  even numbers upto 10
#include <stdio.h>
int main() {
    int N, i = 2;
    scanf("%d", &N);
    while(i <= N) {
        printf("%d ", i);
        i += 2;
    }
    return 0;
}

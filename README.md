#include <stdio.h>

int main()
{
    int start, end, sum=0;
    printf("enter the starting number:\n");
    scanf("%d", &start);
    printf("enter the ending number:\n");
    scanf("%d", &end);
    for(int i=start; i<=end; i++){
        if("i%2==0"){
            sum+=i;
        }
    }
    printf("sum of even numbers:%d", sum);

    return 0;
}

# idk
#include<stdio.h>
int main()
{
    int a=10;
    if(a=11){//here we can see that = is an assignment operator and it is not a boolean expression and its a non zero value this statement is true in the eyes of c compiler. one must use == for this shit
    printf("I am 11");
}
else{
    printf("I am not 11");
}
    return 0;
}

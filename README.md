# strcat-use

#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    char fi[20]="hello ";
    char sec[20]="world";
    strcat(fi,sec);  //combined string gets stored in fi
    puts(sec);
    puts(fi);
    

    return 0;
}




output will be ;-

world
hello world

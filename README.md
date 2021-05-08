# strcat-use

#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    char fi[20]="hello ";
    char sec[20]="world";
    int i,j;
    i=strlen(fi);
    printf("length of string fi before using strcat will be %d \n",i);
    strcat(fi,sec);
    puts(sec);
    puts(fi);
    j=strlen(fi);
    printf("length of string fi after using strcat will be %d ",j);


    return 0;
}



output will be ;-

length of string fi before using strcat will be 6                                                                                                                                  
world                                                                                                                                                                              
hello world                                                                                                                                                                        
length of string fi after using strcat will be 11 

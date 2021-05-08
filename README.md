string functions 

#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    char fi[20]="hello ";
    char sec[20]="world";
    int i,j,k;
   
    i=strlen(fi); // length 
    printf("length of string fi before using strcat will be %d \n",i);
     
    strcat(fi,sec);// combine or concatenate
    puts(sec);// print using puts 
    puts(fi);
    j=strlen(fi);// length 
    printf("length of string fi after using strcat will be %d \n",j);
    k=strcmp(sec,fi);
    printf("\n%d\n ",k);
    if(k>0)
    printf("fi is bigger in ski values as fi is %s and sec is %s\n",fi,sec);
    strcpy(fi,sec);// copy 
    
    printf("we have used strcpy now \n");
    printf(" the fi has become %s, and the sec is %s  ",fi, sec);// print using printf

    return 0;
}



output will be ;-

length of string fi before using strcat will be 6                                                                                                                                  
                                                 world                                                                                                                             
hello world                                                                                                                                                                        
length of string fi after using strcat will be 11                                                                                                                                  
                                                                                                                                                                                   
15                                                                                                                                                                                 
 fi is bigger in ski values as fi is hello world and sec is world                                                                                                                                
we have used strcpy now                                                                                                                                                            
 the fi has become world, and the sec is world

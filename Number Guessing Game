#include<stdio.h>
#include <stdlib.h>
#include <time.h>
int main() 
{
    int n,counter=0;
    int max_attempt=8;

    printf("Enter a number(1-100):");
    scanf("%d",&n);
    
    srand(time(0));
    int number = rand() % 100 + 1;
    
    while(n != number && counter < max_attempt){
    counter++;
    if(n>number){
        printf("Go lower");
    }
    else if(n<number){
        printf("Go higher");
    }
    printf(" ,try Again:");
    scanf("%d",&n);
    }
    counter++;
    
    if (n == number){
        printf("\nYippeee,number is %d",n);
        printf("\nYou guessed it in %d attempts",counter);
        }
        else{
            printf("\nBoo loserrr!!!");
            printf("\nThe number was %d",number);
        }
    return 0;
}

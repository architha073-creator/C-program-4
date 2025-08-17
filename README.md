# C-program-4
IMDB rating 
#include<stdio.h>
int main ()
{
    float IMDB;
    printf("enter");
    scanf("%f",&IMDB);
    if (IMDB>=9.0)
    {
        printf("must watch");
    }
    else if (IMDB>=7.0)
    {    
        printf("good movie");
    }
    else if(IMDB>=5.0)
    {    
        printf("Average");
    }
    else
    {    
        printf("skip");
    }
    return 0;
    }

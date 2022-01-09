#include <stdio.h>
#include <stdlib.h>
 int main ()
    {
        int cont;
        float grade1,grade2,grade3,average;
        grade1=0;
        grade2=0;
        grade3=0;
        average=0;        
        {
            printf ("Write a grade1:");
            scanf ("%f",&grade1);

            printf ("Write a grade2:");
            scanf ("%f",&grade2);

            printf ("Write a grade3:");
            scanf ("%f",&grade3);

            average=(grade1+grade2+grade3)/3;
            if(average>=7)
            {
               printf("Approved the examination\n");
            }
            else
            {
            printf ("Failed the examination\n");
            }         
            printf("The student's average e=%2.f\n",average);
            return 0;
         }
    }

   

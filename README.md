// DATE :- 21-09-2021 TO 23-09-2021
// PROGRAMMER - ANKUR MAURYA

#include <stdio.h>
#include <stdlib.h>
int main()
{
    int select, csize, wsize,count;
    count=1;
    while(count>=1)
    {
        printf(" __________________________________\n");
        printf("|<<<<< SELECT ANYONE OF THEM >>>>>>|\n");
        printf("| 1. Buying T-shirt                |\n");
        printf("| 2. Buying Pant                   |\n");
        printf("| 3. Buying both Pant & T shirt    |\n");
        printf("| 4. About This Software           |\n");
        printf("| 5. Exit                          |\n");
        printf("|__________________________________|\n\n");
        printf("Enter Here >> ");
        scanf("%d",&select);

        switch (select)
        {
        case 1:
            printf("\n1.YOU WANT TO BUY T-SHIRT\n");
            printf("Enter Your chest size in inch\n");
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");
            printf("Enter Here >>");
            scanf("%d",&csize);

            if(csize <= 35 || csize == 36)
                printf("S size T-shirt\n");

            else if (csize == 37 || csize == 38)
                printf("M size T-shirt\n");

            else if (csize == 39 || csize == 40)
                printf("L size T-shirt\n");

            else if (csize == 41 || csize == 42)
                printf("XL size T-shirt\n");

            else if (csize == 43 || csize == 44)
                printf("2XL size T-shirt\n");

            else if (csize == 45 || csize == 46)
                printf("3XL size T-shirt\n");

            else if (csize >= 47 && csize <= 56)
                printf("3XL size T-shirt\n");

            else if (csize >= 56)
                printf("Size More Than 3XL\n");
            break;

        case 2:

            printf("\n2. YOU WANT TO BUY PANT\n");
            printf("Enter Your Waist size in inch\n");
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");
            printf("Enter Here >> ");
            scanf("%d",&csize);

            if(csize >= 24 && csize <= 26)
                printf("XS size Pant\n");

            else if (csize >= 28 && csize <= 30)
                printf("S size Pant\n");

            else if (csize >= 32 && csize <= 34)
                printf("M size Pant\n");

            else if (csize >= 36 && csize <= 38)
                printf("L size Pant\n");

            else if (csize >= 40 && csize <= 44)
                printf("XL size Pant\n");

            else if (csize >= 45)
                printf("size More Than XL\n\n");
            break;

        case 3:
            printf("\n3. YOU WANT TO BUY BOTH\n");
            printf("Enter Your Chest size in inch\n");
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");
            printf("Enter Here >> ");
            scanf("%d",&csize);

            if(csize <= 35 || csize == 36)
                printf("S size T-shirt\n");

            else if (csize == 37 || csize == 38)
                printf("M size T-shirt\n");

            else if (csize == 39 || csize == 40)
                printf("L size T-shirt\n");

            else if (csize == 41 || csize == 42)
                printf("XL size T-shirt\n");

            else if (csize == 43 || csize == 44)
                printf("2XL size T-shirt\n");

            else if (csize == 45 || csize == 46)
                printf("3XL size T-shirt\n");

            else if (csize >= 47 && csize <= 56)
                printf("3XL size T-shirt\n");

            else if (csize >= 57)
                printf("Size More Than 3XL T-Shirt\n");


            printf("\n\nEnter Your Waist size in inch\n");
            scanf("%d",&wsize);

            if(wsize >= 24 && csize <= 26)
                printf("XS size Pant\n");

            else if (wsize >= 28 && csize <= 30)
                printf("S size Pant\n");

            else if (wsize >= 32 && csize <= 34)
                printf("M size Pant\n");

            else if (wsize >= 36 && csize <= 38)
                printf("L size Pant\n");

            else if (wsize >= 40 && csize <= 44)
                printf("XL size Pant\n");

            else
                printf("Size More Than XL\n");
            break;

        case 4:
            printf("# While Buying Any Cloth From any online Store. Many people\n");
            printf("# Facing Problem to Know about his/her Size\n");
            printf("# They Confused in M ,L ,XL ,2XL  \n");
            printf("# No Need to worrie this software will help you :)\n\n");
            printf("# Programmer - Ankur Maurya\n");

            break;

        case 5 :
            exit(0);
        default :
            printf("Press Key b/t 1 to 5\n");
        }
        count++;
    }
    return 0;

}

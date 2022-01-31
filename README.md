include <stdio.h>

int main ()

{

    int pass,seat,booked;

    char user[500];

    printf(" Your name : ");

    

    gets(user);

    printf("\n Enter this fixed password ( 123 ) = ");

    scanf("%d",&pass);

    

    switch(pass)

    {

        case 123:

        printf("\n\t\t\t\t Welcome to ticket booking system\n");

        printf("\n\t\t\t\tAvailable seat = 6 \t Booked seat = 0 \n");

        printf("\n\t\t\t\t Press 1 for booked \t Press any keyword for cancel \n");

        printf("\n\t\t\t\t Please say us what you want........... \t---==> \n");

        

        scanf("%d",&seat);

        switch(seat)

        {

            case 1:

            printf("\n \t\t\t\t Please select your seat number \n");

            printf("\n \t\t\t\t 1\t 2\t 3\t \n\n \t\t\t\t 4 \t 5 \t6 \t ===> ");

        

        scanf("%d",&booked);

        switch(booked)

        {

            case 1:

            printf("\n \t\t\t\t %s,You've Booked seat = 1 \n",user);

            printf("\n \t\t\t\t Available seat = 5 Booked seat = 1 \n");

            break;

            case 2:

            printf("\n \t\t\t\t %s,You've Booked seat = 2 \n",user);

            printf("\n \t\t\t\t Available seat = 5 Booked seat = 1 \n");

            break;

            case 3:

            printf("\n \t\t\t\t %s,You've Booked seat = 3 \n",user);

            printf("\n \t\t\t\t Available seat = 5 Booked seat = 1 \n");

            break;

            case 4:

            printf("\n \t\t\t\t %s,You've Booked seat = 4 \n",user);

            printf("\n \t\t\t\t Available seat = 5 Booked seat = 1 \n");

            break;

            case 5:

            printf("\n \t\t\t\t %s,You've Booked seat = 5 \n",user);

            printf("\n \t\t\t\t Available seat = 5 Booked seat = 1 \n");

            break;

            case 6:

            printf("\n \t\t\t\t %s,You've Booked seat = 6 \n",user);

            printf("\n \t\t\t\t Available seat = 5 Booked seat = 1 \n");

            break;

            default:

            printf("\n\t\t\t\t Invaild seat number \n");

        }

        

        break;

        default:

        printf("\n\t\t\t\t Are you sure want to close it.... press any key ");

        }

    }

    

}

# switch-file
developed by Aarti choudhary
	#include<stdio.h>
main()
{
	//1. Display the menu
	printf("pick an items : \n1. pen\n2. pencil\n3. Eraser\n4. Book");
	//2. read their choice
	int choice=0;
	scanf("%d",&choice);
	//3.display based on their choice
	
	switch(choice)
	{
	case 1:
		printf("you picked pen.");
		break;
    case 2:
    	printf("you picked pencil.");
    	break;
   	case 3:
   		printf("you picked Eraser.");
   		break;
   	case 4:
   		printf("you picked Book.");
   		break;
   	default : printf("Invalide choice");
    }
}

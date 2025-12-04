🎀
compilation of all the activities related to computer programming course
``` c
#include <stdio.h>

int main() {
	printf(" \n");
	printf("\t NOT PERSONAL INFORMATION\t\n");
	printf(" \n");

	printf("NAME \t\t: VINCI \t\n");
	printf("BIRTHDAY \t: AUGUST xx, xxxx \t\t\t AGE \t\t:18 years old \n");
	printf("ADDRESS \t: SOMEWHERE FAR FAR AWAY FROM HERE\n");
	printf("HEIGHT \t\t: X'Xft \t\t\t\t WEIGHT \t: XXkg. \n");
	printf("STATUS \t\t: GUESS \n");
	
	printf("----------------------------------------\n");
	
	printf("\t EDUCATIONAL BACKGROUND \t\n");
	printf("TERTIARY \t: \v FAR FAR AWAY WHERE I AM TRYING TO BE FREE \t\t IDK \t\t 202x \n");
	printf("SECONDARY \t: \v SOMEWHERE FAR WHERE I FINALLY START TO SPREAD MY WINGS  \t\t 20xx \n");
	printf("PRIMARY \t: \v SOMEWHERE FAR WHERE I THOUGHT I AM FREE \t\t\t 20xx \n");

	return 0;
}



// above are the escape sequences

// user input

#include <stdio.h>

int main() {
    printf("=============================================\n");
    printf("\t PERSONAL INFORMATION FORM \t\n");
    printf("=============================================\n");
    
    char Fname[20];
    printf("\nEnter your First name: ");
    scanf("%s", Fname);
    
    char Lname[20];
    printf("\nEnter your Last name: ");
    scanf("%s", Lname);
    
    char num[15];
    printf("\nEnter your number: ");
    scanf("%s", num);
    
    printf("\n---------- Date of Birth ---------- \n");
    
    char month[15];
    int day, year;
    
    printf("\nMonth: ");
    scanf("%s", month);
    printf("\nDay: ");
    scanf("%d", &day);
    printf("\nYear: ");
    scanf("%d", &year);
    
    printf("=============================================\n");
    printf("\t PERSONAL INFORMATION \t\n");
    printf("=============================================\n");

    printf("\nName\t\t: %s %s", Fname, Lname);
    printf("\nDate of Birth\t: %s %d, %d", month, day, year);
    printf("\nMobile number\t: %s", num);
    
    return 0;
}



// loops bro

#include <stdio.h>

int main()
{
    // for loops
    
    printf("Activity 4: Repetitive \n");
    printf("------------------------------\n");
    printf("#1 For loop\nProblem: Square of all odd numbers 23-31 \n");
    printf("Answer: \n");
    
    for (int i=23; i<=31; i+=2) {
        printf("%d^2=%d \n",i, i*i);
    }
    
    
    // while loops
    
    printf("------------------------------\n");
    printf("------------------------------\n");
    printf("#2 While loop\nProblem: Sum of all even numbers between 15-25 \n");
    
    int k=16;
    int sum=0; //
    while (k<=25) {
        sum+=k; // to add them
        k+=2; //for da next number to add to sum and whatever the answer will become new sum and then will add again to the next number who are plus 2 from previous 
    }
    printf("Answer: Sum is %d \n", sum);
    
    printf("------------------------------\n");
    printf("------------------------------\n");
    
    
    
    // do while
    
        printf("#3 Do while loop\nProblem: Ask the user for number divisible by 6 \n");
    printf("Answer: \n");
    
        int j;
        
        do {
            printf("Enter a number divisible by 6: ", j);
            scanf("%d", &j);
    // no i++ here because it is not working kapag nakalagay dito 
        } while (j % 6 != 0); // for computation that j is divided by 6 and the answer should not be zero kasi mali na yun
        
        printf("Correct! %d is divisible by 6", j);
        
        
    return 0;
}


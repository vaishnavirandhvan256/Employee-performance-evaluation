# Employee-performance-evaluation
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int productivity, teamwork, communication, innovation;
    int total;
    float average;

printf("Enter your productivity score:");
scanf("%d", &productivity);
printf("Enter your teamwork score:");
scanf("%d", &teamwork);
printf("Enter your communication score:");
scanf("%d", &communication);
printf("Enter your innovation score:");
scanf("%d",&innovation);

  // Calculate total and average
    total = productivity + teamwork + communication + innovation;
    average = total / 4.0;

  printf("\nTotal Score: %d\n", total);
    printf("Average Score: %.2f\n", average);

  //display performance remark
    if (average >= 80){
        printf("Performance: Excellent!\n");
    }else if (average >= 60){
        printf("Performance: Good.\n");
   } else if (average >= 40){
        printf("Performance: Average.\n");
    }else{
        printf("Performance: Needs Improvement.\n");
}



return 0;
}

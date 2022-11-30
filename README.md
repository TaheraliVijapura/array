# array
#include <stdio.h>

int main (){
  int rollno[10], marks[20],i;

  for (i=0;i<10;i++) 
  {
    printf("Enter Roll of Student %d\n", i + 1);
    scanf("%d", & rollno[i]);
    printf("\n Enter Mark of Student %d\n", i + 1);
    scanf("%d", & marks[i]);
  }

  for (i = 0; i < 20; i++) {
    printf("\n Roll No :  %d   Marks : %d", rollno[i], marks[i]);
  }

  return 0;
}

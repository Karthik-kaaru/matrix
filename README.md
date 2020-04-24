# matrix
To find the sum of diagonal of matrix using arrays n pointers
#include <stdio.h>
const int MAX=3;
const int MIN=3;
int main() {
  int mat[MAX][MIN]={};
  int i,j;
  printf("enter the elements\n");
  for(i=0;i<=3;i++)
  {
      for(j=0;j<=3;j++)
      {
          scanf("%d",&mat[i][j]);
      }
  }
  int *p[MAX][MIN];
  p=mat[MAX][MIN];
  for(i=0;i<=3;i++)
  {
      for(j=0;j<=3;j++)
      {
        printf("the elements are %d\t",*p[i][j]);
        }
    }
  for(i=0;i<=3;i++)
  {
      for(j=0;j<=3;j++)
  {
     int d=0;
     if(i==j)
     d+=m[i][j];
     break;
     }
     }
     printf("the sum of diagonal elements are %d",d);
     
      return 0;
}

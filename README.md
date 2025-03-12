# c-16
Hollow square
#include <stdio.h>
int main() 
{
    int i,j,n,m;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
    printf("enter the column of the matrix:");
    scanf("%d",&m);
    for(i=1;i<=n;i++){
        for(j=1;j<=n;j++){
            if(i==1||i==n||j==1||j==m){
                printf("* ");
            }else{
                printf("  ");
            }
        }
        printf("\n");
    }
    return 0;
}

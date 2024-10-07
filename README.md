//calculate-the-percentage
#include <stdio.h>

int main()
{
 int bee,maths,pbl,c,cs,avg,per;
 printf("enter the marks of five subjects:");
 scanf("%d%d%d%d%d",&bee,&maths,&pbl,&c,&cs);
 avg=(bee+maths+c+cs+pbl)/5;
 printf("avg is = %d\n",avg);
 per=(bee+maths+pbl+c+cs)*100/500;
 printf("per is=%d\n",per);

    return 0;
}

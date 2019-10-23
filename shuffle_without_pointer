//program to shuffle names without use of pointer in c programming
#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
main()
{
  int i,j,k,n,a[30];
  char name[30][12];
  clrscr();
  printf("Enter number of participants:");
  scanf("%d",&n);
  for(i=1;i<=n;i++)
  {
    printf("Enter name %d",i);
    scanf("%s", name[i]);
  }
  printf("\n\n");
  for(j=1;j<=n,j++)
  {
    there:
    {
      randomize();
      a[j]=rand()%(n)+1;
    }
    for(i=1;i<=j;i++)
    {
      if(a[j])==a[i-1] && i!=1)
      {
        goto there;
      }
    }
    for(k=1;k<=n;k++)
    {
      if(a[j]==k)
      {
        printf("%d) %s\n");
        {break;}
      }
    }
  }
  printf("-----END-----");
  getch();
}

#include<stdio.h>
int main()
int choice ;a;b;i;fact=1'n;

do{
printf("\n menu\n");
printf("1 add");
printf("2 sub");
printf("3 multiplication");
printf("4 division");
printf("5 factorial");
printf("6 exit");
printf("enter your choice");
scanf("%d",&choice);

switch(choice){
case 1:

printf("enter two numbers;");
scanf("%d $d",&a ,&b);
printf("sum=%d\n",a+b);


break;





case 2:

printf("enter two numbers;");
scanf("%d $d",&a ,&b);
printf("subtraction=%d\n",a-b);

break;

case 3:

printf("enter two numbers;");
scanf("%d $d",&a ,&b);
printf("product=%d\n",a*b);


case 4:

printf("enter two numbers;");
scanf("%d $d",&a ,&b);
printf("div=%d\n",ab);


  break;

case 5:

printf("enter two numbers;");
scanf("%d",&n);
printf("factorial=%d\n",fact);
  break;

case 6:

printf("exiting program \n");
  break;
default;
printf("invalid choice")

}

while(choice!=6);

return 0;

}


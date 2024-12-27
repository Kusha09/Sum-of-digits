# Sum-of-digits
This is a c program about adding sum of n-digits
#include<stdio.h>
int main (){
 int n,sum,lastdig;
 printf("Enter a number:");
 scanf("%d",&n);
 sum=0;
 lastdig=0;
 while(n!=0){
   lastdig=n%10;
   sum=sum+lastdig;
   n=n/10;
   
 }
  printf("the sum of digits are:%d\n",sum);
  return 0;
}

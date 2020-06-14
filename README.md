# reverse-numbers
#include <stdio.h>
int main(){
  long long int reversia = 0;
  int n, nashti, k;
  {
  scanf ("%d", &n);
  while(n!=0){
    nashti = n % 10;
    reversia = reversia * 10 + nashti;
    n /= 10;
  }
  }
  
  printf("%lld\n", reversia);
  return 0;
}

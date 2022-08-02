#include <stdio.h>
#include <math.h>
const int MAX=int(1e5);
bool prime(int n)
{
	for(int i=3;i*i<=n;i+=2)
		if(n%i==0)return 0;
	return 1;
}
int main()
{
	printf("2\n");
	for(int i=3;i<MAX;i+=2)
	{
		if(i%5==0)continue;
		if(prime(i))printf("%d\n",i);
	}
  return 0;
}

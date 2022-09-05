# code
这是一个小白的代码库
计算n！
#include <stdio.h>
int main()
{
  int i=0;
  int ret=1;
  scanf("%d",&n);
  for(i=1;i<=n;i++)
  {
     ret=ret*i;
  }
  printf("ret=%d \n",ret);
  return 0;
}

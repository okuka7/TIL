# a + b + c
 
```
#include <stdio.h>

int main(void)
{
	long long a b c;
	scanf("%lld %lld %lld",&a,&b,&c);
	printf("%lld",a+b+c);
	return 0;
}
```

간단한 문제였는데 자료형의 크기를 고려하지 않았다.  
입력 조건에 __첫 번째 줄에 A, B, C (1 ≤ A, B, C ≤ 1012)이 공백을 사이에 두고 주어진다.__ 라는 조건이 있었으므로 int이상의 크기를 고려했어야 했다.

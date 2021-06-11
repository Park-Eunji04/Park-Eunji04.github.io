---
layout: single
title: "비트 연산자"
toc: ture
toc_sticky: true
toc label: "페이지 주요 목차"
---
### 01. 비트 연산자의 정의
비트 연산자는 비트 단위로 논리 연산을 할 때 사용하는 연산자이다.
비트 연산자는 비트로 옵션을 설정할 때 주로 사용하며 저장 공간을 아낄 수 있는 장점이 있다. 

### 02. &
대응되는 비트가 모두 1이면 1을 반환함. (비트 AND 연산)

[AND 연산자]
~~~c
int main()
{
int a,b;

printf("a b : ");
scanf("%d%d", &a, &b);

if(a>0 && b>0)
printf("a>0 && b>0의 결과는 참이다.\n");
else
printf("a>0 && b>0의 결과는 거짓이다.\n");
return 0;
}
~~~ 

### 03. |	
대응되는 비트 중에서 하나라도 1이면 1을 반환함. (비트 OR 연산)

### 04. ~	
비트를 1이면 0으로, 0이면 1로 반전시킴. (비트 NOT 연산)

### 05. <<	
지정한 수만큼 비트들을 전부 왼쪽으로 이동시킴. (left shift 연산)

### 06. >>	
부호를 유지하면서 지정한 수만큼 비트를 전부 오른쪽으로 이동시킴. (right shift 연산)

### 07. 참고 자료
![bitwise operator](/assets/images/9946.png)
{% include video id="8P6RXhBp_sM" provider="youtube" %}

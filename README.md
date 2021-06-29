# Programmers_python
## 2021-06-25 금요일 
프로그래머스에서 처음 해봄. 분명 쉬운 것 같은데 아무것도 되지 않는다. 이번 방학 때 파이썬으로 계속 공부해볼 생각이다

:hash_1 // 프로그래머스 

## 2021-06-26 토요일
여기서는 lambda 함수가 많이 사용된다. 이것을 특히 더 잘 알 수 있도록 다음에 관련해서 정보를 적어보겠다

++lambda를 사용할 때는 List나 map을 같이 사용한다. lambda x : x +10 이라고 하면 무명의 함수를 만들어내는 것이다. 앞에 a = 을 붙여주면 def를 통해서 method를 만든 것처럼

똑같이 함수를 생성할 수 있는 것이다. 즉 위의 예시에서는 a(10)을 하면 20이 return 되는 것을 볼 수 있다. *2021-06-29

## 2021-06-28 월요일
이번에 푼 것은 프로그래머스에서 소수 만들기이다. 이 코드를 작성할 때 제일 어려웠던 부분은 combination을 짜는 부분이었다. 결국 import를 해서 combination을 표현했다.

from itertools import combinations 를 이용하였고 사용할 때는 list(combinations(list 이름, 뽑아낼 원소의 개수)) 로 해주면 된다.

## 2021-06-29 화요일
문제 내용은 어렵지 않았다. 두 개의 list가 주어졌을 때 내적을 구하는 것이다. for 구문을 이용해서 각각의 원소끼리 곱해서 총 합을 구해주면 되는 것이다. 하지만 여기에서의 키워드는 zip 이다.

zip(a,b) 를 하면 각 list에서의 같은 자리의 원소끼리 zip이 되는 것을 볼 수 있다. 

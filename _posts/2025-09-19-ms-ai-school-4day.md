---
layout: post
title: "Microsoft AI School 네번째 날"
date: 2025-09-19
---

# 오늘 ms ai school 에서 배운것
## python 교육
 - python을 본격적으로 배우기 시작
 - 자료형(string, int, float)등에 대해서는 기존에 알던거랑 같아 복습하는 느낌으로 다시 공부
 - True, False 등의 자료형 type 음 bool (논리형)
 - input 함수 여러번 사용해봄 보통
  변수 = int(input("원하는 숫자를 입력해서요")) 식으로 사용
 - print 함수의 새로운 기능 배움. VS Code에서 함수에 마우스 커서를 가져다 데면 나옴. print(~~, **end= " "**) 이런식으로 end 뒤를 어떻게 할지 가능. 그밖에 sep?도 있음. (기본값 end = \n 임)
 - 다음으로, 조건문, 반복문에 대해서 배움. 이것도 아는거라 복습위주 느낌으로 함. 다만 while 조건문은 평소에도 헷갈렸기에 다시 정리

## while 반복문
 - 기본형태: while 조건:
 - 사용하는 경우: 보통 for 은 반복문을 반복하는 횟수가 정해져있을때 주로 사용. 반면, 몇번 반복할지 정해지지 않았다면 보통 while 반복문 사용
 - 기본형태 설명: while 조건: 에서 조건 == True 일 때 아래 함수나 반복문등을 반복함. False가 되는 순간 작동 멈춤.
 - 반복문 + 조건문: while 조건: -enter 키 치고 아래에 조건문 쓰는것 가능. 물론 for등에도 사용가능. 조건문은 if elif else 순으로 가며, 이때 서로 다른 조건?(관련성 없는? 혹은 목적이 다른?) 조건문은 elif 가 아닌, 별도 if로 쓰는게 더 직관적. if, if 여러개 써도됨
 - continue, break : continue는 해당하는 경우에는 반복문 수행하지말고  넘너가라는 뜻. break 는 반복문 종료하고 빠져나오라는 뜻.
 - 예시(숫자맞추기 게임):
import random
answer = random.randint(1,100)
i = 1
while num_input != answer:
    num_input = int(input("1부터 100사이의 숫자를 맞춰주세요"))
    print(f"1부터 100 사이의 숫자를 맞춰주세요: {num_input}")
    if num_input > answer and i != 5:
        print(f"너무 커요. {i}번째 시도하셨습니다. 기회가 {5 - i}번 남았습니다.")
    elif num_input < answer and i != 5:
        print(f"너무 작아요. {i}번째 시도하셨습니다. 기회가 {5 - i}번 남았습니다.")
    elif i == 5: 
        print("펑! 실패하셨습니다.")
        break
    else:
        print("정답입니다.")
        break
    i += 1

## 이중 반복문
- 이중 반복문은 for 과 for 등을 연속해서 사용하는것
- 예시(구구단 만들기):
dan = 1
j = 1
for dan in range(1, 10):
    for j in range(1, 10):
        print(f"{dan} x {j} = {dan * j}")

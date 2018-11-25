# hansei-embedded-system

![1](https://user-images.githubusercontent.com/39250642/46917527-48396380-d003-11e8-8a3c-2ce134501bbe.png)
![2](https://user-images.githubusercontent.com/39250642/46917535-643d0500-d003-11e8-90a4-bf4f2b0f140f.png)
![3](https://user-images.githubusercontent.com/39250642/46917536-656e3200-d003-11e8-9e44-f0a862f11e31.png)
![4](https://user-images.githubusercontent.com/39250642/46917537-669f5f00-d003-11e8-94ee-87df6e6ee93a.png)
![5](https://user-images.githubusercontent.com/39250642/46917538-6737f580-d003-11e8-8e5c-bf2de3321113.png)
![6](https://user-images.githubusercontent.com/39250642/46917540-68692280-d003-11e8-8b02-0ca9cfe8102e.png)
![default](https://user-images.githubusercontent.com/39250642/46917652-69e71a80-d004-11e8-9a91-aadc24a8279a.png)
![8](https://user-images.githubusercontent.com/39250642/46917543-6c954000-d003-11e8-8e35-649542c0aebb.png)

관련 링크 http://www.iotdanawa.com/archives/3390


http://www.devicemart.co.kr/1341781 lcd
http://www.devicemart.co.kr/33870 압력센서
http://www.devicemart.co.kr/1322885 컴버터








2018/11/12
프로젝명 : 스마트 저금통

금주 실습한 내용

실습명 : 데이터 베이스에 있는 값 읽어오기


실습절차

1)sqlite3을 통해 가장의 통장 생성

2)통장의 임의의 money저축

3)카카오 플친을 통해 통장 잔고 확인 (실패)

결과

ㄱ)데이터 베이스(sqlite3)에 값 입력 하기 성공

ㄴ)입력한 값 저장까지 완료

ㄷ)u+포트포워딩이 되지 않아 카카오와 연동 실패

결론

A)iptime 무선공유기를 구한뒤에 포트포워딩 성공하기

B)카카오 플러스 친구 ui 구성하기 ex)통장 금액 확인, 비밀번호 변경 등



관련 링크 https://blog.naver.com/roboholic84/221363480611 챗봇과 DB

----------------------------------------------------------------------------------------------------------------------------------------



2018/11/12 (예상 계획)
프로젝명 : 스마트 저금통

금주 실습할 내용

실습명 : 압력 센서로 동전 구별 하기

실습 절차

1)라즈베리 파이와 압력 센서 연동 하기

2)압력센서로 받은 값을 로직을 통해 압력에 따른 무게로 10원,50원,100원을 구별

3)구별한 값을 sqlite3에 있는 가상의 통장 잔고에 money를 저장

4)카카오 플친으로 통장 잔고 확인하기 

5)압력센서로 값 읽기 실패시 그냥 압력센서에 압력만 주면 100원을 DB에 저장하겠금 만들기.

결과

ㄱ)카카오 플러스친구로 통장안의 금액을 확인할 수 있음

ㄴ)압력센서로 동전을 구별 한 뒤 다양한 금액을 저금 함

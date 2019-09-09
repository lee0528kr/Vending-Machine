# Vending-machine-console-

2019.08.30 (금) ~ 2019.09.06(금)
쌍강교 1조 - Vending Machine with KIOSK
(팀 과제 - 팀장 : 이예림 / 조원 : 이현지, 이성조, 박혜민, 최창훈, 오지은)

* DB를 이용하지 않고 java만으로 만든 키오스크 기반 Cafe & Pub 자판기.

총 9개의 클래스와 1개의 인터페이스로 구성되어 있으며, 메인클래스는 Mainmachine 클래스이다.

또한 Cafe, Pay, Beer, Adult, Mainmachine은 Admin을 상속받으며, Cafe클래스는 추가로 Recipe 인터페이스를 
implements 받는 형식으로 구성하였다.

**************기능 설명**************
1. 커피 OR 맥주 선택주문
2. 장바구니 기능 탑재
3. 맥주구매시 성인인증 기능 탑재
4. 성인인증시 주민번호, 휴대폰번호 정확하게 입력시 임의의 인증번호 난수로 발생.
5. 결제기능은 3가지(현금, 카드, 쿠폰)
6. 현금결제시 기계내에 남은 거스름돈 수량에 따라 경우의수 다 따져 거스름돈 반환.
7. 10번 결제시 1번 쿠폰지급.(3000원 할인 쿠폰)
8. 카페종류6가지, 맥주종류5가지
9. 관리자모드7가지 기능
  - 총매출
  - 재고 관리
  - 거스름돈 관리
  - 가격 설정
  - 비밀번호 변경
  - 사용시간(고장율) 확인
  - 재부팅 시작
10. SimpleDateFormat 와 format.DateTimeFormatter를 이용하여 현재시간을 밀리초로 받아와 yyyy/mm/dd HH:mm:ss형태로 변형하여 출력하는 형태로
    사용시간 및 고장율 확인.



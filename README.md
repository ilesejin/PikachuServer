# PikachuServer
A serving program for Pikachu Volleyball
![image](https://user-images.githubusercontent.com/35063338/212844981-4ede4b74-d5cc-43c7-a2c2-e3471b6bffe9.png)

## 사용법
T = 초기화, Y = 재생/정지

, = 1프레임 전으로, . = 1프레임 다음으로

Frame 번호 입력하여 원하는 프레임으로 이동 가능

FPS: 시간당 프레임(빠르게: 32~34)

1p, 2p 좌표 표시, Ba: 공 좌표/Bv: 공 속도 

## 코드 문법
코드를 입력하여 서브 제작(코드 입력 후 T로 초기화, Y로 재생)

위: U, 아래: D, 왼쪽: L, 오른쪽: R, 스파이크: H

/로 1p와 2p 구분, -로 프레임 구분

숫자로 하나의 명령어 반복(공백은 무시)

ex) R/L 2 - / 20: 1p, 2p가 각각 앞으로 2틱 이동 후 정지

1p 뒤돌려 v찍기: R/-/21-R/32-RUH/-/16-DH/

1p 7타: R/-/21-R/46-U/-/14-RH/-/14-RUH/-/19-U/3-RUH/-/17-RH/-RUH/41-U/13-DH/

1p 땅긁기: R/-R/-/21-UR/-R/15-/15-RH/-/8-U/-/3-RH/

# Pikachu Server
피카츄 배구 서브 개발 프로그램

Made by 엑사바이트🔌

Thanks to 피카츄배구 온라인(https://open.kakao.com/o/g69cU1Ic)
![image](https://github.com/user-attachments/assets/62a82eac-ffcd-4429-b8c9-524a93c90403)

## 다운로드 방법
![image](https://user-images.githubusercontent.com/35063338/213129585-4f86071d-fb27-476b-8142-3f575fe6c932.png)
Code 클릭 후 Download ZIP 클릭!
![image](https://user-images.githubusercontent.com/35063338/213129807-036a8890-bddd-4765-a254-68297774158d.png)
다운 받은 파일에서 압축 풀기 후 피카츄 아이콘 클릭하면 실행됩니다!


# 사용법
## 기본 단축키
T = 초기화, Y = 재생/정지

, = 1프레임 전으로, . = 1프레임 다음으로

Frame 번호 입력하여 원하는 프레임으로 이동 가능

적용: 바뀐 코드를 적용하여 다시 현재 프레임으로 이동

FPS: 시간당 프레임(빠르게: 32~34)

1p, 2p 좌표 표시, Ba: 공 좌표/Bv: 공 속도 

## 코드 문법
코드를 입력하여 서브 제작(코드 입력 후 T로 초기화, Y로 재생)

위: U, 아래: D, 왼쪽: L, 오른쪽: R, 스파이크: H

/로 1p와 2p 구분, -로 프레임 구분

랜덤 고정: 한 명령어 이후 ~로 추가하여 공 속도가 0이 되었을 때의 랜덤값 설정(L: -1, M: 0, R: 1)

숫자로 하나의 명령어 반복(공백은 무시)

ex) R/L~M2-/20: 1p, 2p가 각각 앞으로 2틱 이동 후 정지, 그동안 랜덤값은 0

<1p 뒤돌려 v찍기>
R/-/21-R/32-RUH/-/16-DH/

<1p 7타>
R/-/21-R/46-U/-/14-RH/-/14-RUH/-/19-U/3-RUH/-/17-RH/-RUH/41-U/13-DH/
(36/416에서 x축 속도 반전)

<1p n타>
R/-/21-R/46-U/-/14-RH/-/14-RUH/-/19-U/3-RUH/-/17-RH/-U/14-RUH/-U/22-RUH/-/8-U/8-RUH/-/20-RUH/-U/16-RUH/-U/21-RUH/-/20-RUH/-U/17-RUH/-/15-RUH/-/17-U/4-RUH/-/14-RDH/-/20-U/5-RUH/-/22-RUH/-/11-U/6-RUH/-/15-RUH/-/18-U/3-RUH/-/14-RDH/-/20-U/5-RUH/-/22-RUH/-U/17-RH/-/14-RUH/-/18-U/4-RUH/-/15-RDH/-U/22-RUH/-/55-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RUH/-/17-U/3-RUH/-/14-RDH/-
U/22-RUH/-/16-RH/

<1p 땅긁기>
R/-R/-/21-UR/-R/15-/15-RH/-/8-U/-/3-RH/

<1p 렉대각긁기>
R/2-/24-RU/20-/9-L/-LH/-L/-/3-RUH/-L/2-RH/

<1p 렉위긁기>
R/2-/24-RU/20-/9-L/-LH/-L/-/2-R/-UH/-/-RH/

<1p 더블어택 찍기>
R/2-/22-U/-R/15-/11-H/-RU/7-RDH/

<2p 공중 네트 찍기>
/L6-/30-/L-/UL-/L7-/5-/H-/L11-/HD
/2-/LU8-/2-/H-/L14-/LDH

<1p 공중 네트 찍기>
/2-UR/8-/2-H/-R/14-RDH/
R/5-/32-UR/6-/6-H/-R/13-DH/
R/5-/20-R/6-/6-U/6-/6-H/-R/13-DH/

<2p 소츄 5타>
/L2-/23-/UL17-/12-/L27-/UL-/ULH-/17-/LDH-/UL15-/7-/ULH-/20-/ULH-/UL3-/14-/LDH

<2p 썬더>
/L-/23-/L30-/ULH-/14-/DH10

<1p 금주 썬더>
R/6-/20-UR/20-/20-UR/-/17-RDH/3-RUH/-U/16-DH/

<1p 5틱 자가 속공 뒤돌려 찍기>
R/5-/18-U/-R/6-/24-H/-R/6-/3-UR/7-URH/-/14-DRH/

<1p 5틱 자가 속공 찍기>
R/5-/18-U/-R/6-/24-H/-R/8-RU/4-RDH/

<불꽃놀이>
R/-/20-R/4-UR/25-URH/-/19-U/2-URH/-L/10-/3-DRH/-R/20-U/3-URH/-L/10-/3-DRH/

<카이 3타>
/9-RU/30-/5-U/-RUH/-/16-RUH/-U/17-RUH/-/14-RDH/-/14-U/-/7-RUH/-/15-RDH/

<높은 속공>
R/-/19-U/-L/2-/-R/-RH/

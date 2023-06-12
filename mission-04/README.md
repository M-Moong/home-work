#grid를 이용한 레이아웃 배치 - 새소식


![image](https://github.com/M-Moong/home-work/assets/109510367/919ca85d-fed3-4dc9-9a79-8ae402b555ff)


---
###마크업

이번 과제는 그리드가 주 작업이자 핵심이지만 여러가지 태그를 계속 사용해 보고싶어 최대한 여러 종류의 태그를 사용해보았습니다.

![image](https://github.com/M-Moong/home-work/assets/109510367/e65061d5-6390-447f-9e11-d930cdc2ca51)


주석으로 그리드 item을 순서별로 나누며 마크업 하였습니다

---
###CSS

처음에는 container에 display: grid;주고 grid-template-areas 주었는데 계속 적용이 되지 않았습니다.

mdn과 강사님의 피드백으로 알게 되었습니다. areas에 주는 이름은 순수 string 타입만 가능합니다.

처음에 숫자로 주었던 부분이 문제였습니다. 피드백을 받고 난뒤 grid-template-areas의 속성으로 단번에 위치를 설정하였습니다.

--

![image](https://github.com/M-Moong/home-work/assets/109510367/5fa686e8-6f13-46dc-b3dc-eb997c56ed66)

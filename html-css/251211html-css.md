251211 HTML-CSS 학습하기
========================
## 오늘의 목표
- 6-4과 : 배경속성
- 6-5과 : 위치속성
- 6-6과 : 전환효과

## 학습 내용

1. 배경속성
- 배경 = padding + content
- background-color/image : 색상 넣기, 그림 넣기
 + :색상값 / url()
 + 반드시 요소의 배경 크기 설정 필요 : width, height 앞서서 정의
- image는 크기 안 맞으면 기본적으로 잘리거나 반복해서 넣는다.
 + background-repeat : repeat, repeat-x/y, no-repeat, round(자동조절), space(안 잘릴때까지만 반복)
 + background-size : auto, cover(가장 큰 변에 맞춰서 넣고 자른다.), contain(비율을 맞게 맞춰서 넣는다.), <너비 높이>(직접지정)
 + background-position : 위치 지정, right/center/left, %이용 가능
 + background-attachment : local, scroll, fixed => fixed만 아니면.. 상관없을 듯하다. 사실 이 부분은 잘 이해 못했다.
- background 로 한번에 지정 가능하지만 지양하자.


2. 위치속성
- 앞서 배운 태그별 속성을 알아야 한다.
 + 블록성격: hn, div, p => 한줄 다 먹기, 다음 것은 줄바꿈
 + 인라인 성격 : span, a, strong => 한줄로 배치
 + 인라인 블록 성격 : img => 요소의 너비만 블록
- position
 + static : 기본 흐름
 + relative, absolute : 요소의 왼쪽 위 기준점, 웹페이지의 왼쪽 위 기준점
 + fixed : absolute로 좌표 찍고 스크롤과 무관한 위치 사수
 + sticky : 스크롤에 따라 움직이다가 특정 위치에서 fixed 발동
- z-index : 앞으로 보내기 뒤로 보내기, 정수값!
- float : 가장 어려운 부분, left와 right
 + 블록 요소를 인라인 요소로 표현 가능
 + 모두 float걸어주고 다음에 풀어줘야 한다. by clear와 :after로
 + clear : left, right, both
  - 이전 float를 지워준다. 즉 직전 float에 영향을 받지 않게 된다.


3. 전환효과
- transition-property/duration/timing-function/delay
- property와 duration은 필수다.
 + property : 전환효과를 주고 싶은 속성값
 + duration : 전환효과의 지속시간, 효과가 걸리는 총 시간
- timing-function
 + 키워드 : linear, ease, ease-in, ease-out, ease-in-out
 + cubic-bezier(,,,): 크롬 개발자 도구에서 속도 조절 가능
 + [cubic-bezier 계산 사이트](https://cubic-beizer.com)


## 느낀점
클래스와 가상클래스를 능숙하게 읽어야 CSS 활용이 쉬워진다.
:nth-child 부분을 복습했다.

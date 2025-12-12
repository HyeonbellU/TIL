251212 HTML-CSS 학습하기
=========================
# 오늘의 목표
- 6-7,8,9과 학습 마무리
- 그동안 작성한 md 파일들 git 업로드 확인

# 학습 내용
1. 애니메이션 속성
- 목적 : 전환효과의 정확한 제어
- 주요 내용 : 스타일 속성, 키프레임
## 키프레임(@keyframe)
- 3요소 : 이름, 시작(from, 0%), 끝(to, 100%)

- animation-name/duration/delay : 키프레임 이름, 지속시간, 지연시간
## 기본적으로 한번 실행, 이후 원 상태로 복귀

- animation-fill-mode : 시작부터 적용OX, 끝난 뒤 적용OX
 + 시작전 적용 X: none, forwards(가장 다용)
 + 시작전 적용 O: backwards, both
- animation-iteration-count: 숫자 or infinite
- animation-timing-function: 전환과 동일하게 작용
- animation-play-state: 재생상태 => JS 필수... 나중에 보자!
- animation-direction: from과 to를 어떻게 진행할지(normal과 reverse)
 + alternate, alternate-reverse : 홀수번째, 짝수번째를 다르게 운영
- animation 속성으로 한번에 지정이 가능하다.


2. 변형 효과
- 목적 : ~~요소의 속성~~요소 자체의 변형
## transform 속성
- translate: 이동
- scale: 크기 변경
- skew: 기울기
- rotate: 회전
- 변형을 시작하는 기준점은 항상 요소의 중심점
=> transform-origin 속성: 좌표 or (left, right, center)

3. 웹/아이콘 폰트
- 텍스트 속성과 연계: 6.2 텍스트 속성
## 웹폰트
- 시스템에 없는 글꼴
- link태그
- @import구문 : style태그의 최상단 삽입 => font-family 속성에 적용 가능

## 아이콘 폰트
- Font Awesome, Material Icon
- 아이콘 라이브러리 다운 또는 CDN 사용
- [CDNJS 사이트](https://cdnjs.com/libraries/font-awesome)
- CDN 주소를 head 태그 안에 넣는다 : link 태그로 제공
- [FontAwesome사이트](https://fontawesome.com/icons)에서 검색 후 태그 복사

# 느낀점
- git 업로드 후 확인하자.
- JS를 어서 배워야 실무적 활동이 가능하니 빨리 진도를 나가자.

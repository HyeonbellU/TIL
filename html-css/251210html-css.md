251210 html-css 독학
=====================

## 오늘의 목표
- 6장 1,2,3과

## 학습 내용
1. CSS의 특징
- 적용 우선순위
 + 전체 선택자
 + 태그 선택자, 가상요소 선택자(::)
 + 클래스 선택자, 가상클래스 선택자
 + 아이디 선택자
 + 인라인 스타일
 + !important
- 단위
 + 절대단위 : px
 + 상대단위 : %, em, rem, vw, vh
- 색상표현 : RGBA, HEXA

2. 텍스트 속성
- font-family : generic family를 뒤에 첨부하기
 + serif, sans-serif, monospace, fantasy, cursive
- font-size, font-weight, font-style, text-decoration, color : 크기, 굵기, 기울기, 줄긋기, 색상
 + 굵기 : 100단위, normal(400), bold(700)
 + 기울기 : italic(폰트 내재), oblique(기울이기)
- font-variant : 소문자를 작은 대문자로
- text-align, letter-spacing : 정렬, 자간
 + left, right, center, justify(양쪽 정렬)
- line-height
 + 한줄의 높이 = top과 bottom line의 사이 거리= font-size + 행간
 + font-size는 중앙에 위치
 + 영어는 baseline이 존재

3. Box model
- margin, border, padding, content
- margin, padding : 설정방법 동일
- border : 두께, 스타일, 색상
- content : box-sizing 속성을 "border-box"로 설정하기
- 요소의 크기 = border+padding+content

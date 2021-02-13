# spartacodingclub
스파르타코딩클럽 21년 신년운세 패키지

1일차 

강의자료
https://www.notion.so/1-4b2f8f0a33c04b2d8fd1604458480a71#4f468921ef9b4e2eb041a1940e500047

1. 설치프로그램
  크롬 다운로드(https://www.google.com/intl/ko/chrome/)와
  VS Code 다운로드(https://code.visualstudio.com/download)
2. 배울 내용
  신년운세(https://new-year.spartacodingclub.kr/) 완성 페이지 예시
  서버/클라이언트/웹의 동작 개념
3. HTML, CSS 기본내용
  HTML과 CSS의 개념
  HTML 기초
    - sample.html을 통한 구성 예시 확인
    - 확장프로그램 open in browser 설치
4. CSS 기초
  누구를. 어떻게 할 것인가의 문제. (식별자)
5. CSS 적용하기 - 배경
  background-repeat : no-repeat;
    - 이미지를 반복하지 않도록 처리
  background-image: url("");
    - 이미지 삽입
6. 폰트 입히기
  https://fonts.google.com/?subset=korean
7. CSS 적용하기 - 르탄이들(1)
  `width`, `height` 값을 150px로!
  모서리는 - `border-radius` 로!
  테두리는 - `border` 로!
  배경은 - `background-color` 로!
  그림자는 - `box-shadow` 로!
  a태그는 - 텍스트 속성이라서 `display:block` 속성을 줘서 글 속성을 박스로 변경

  - flex 속성은 div 안의 내용물을 정렬하는 방법
- `display:flex`
- `flex-direction:row`
- `justify-content:center` 세가지가 기본적으로 같이 다닌다고 생각해야 함.
8. CSS 적용하기 - 르탄이들(2)
  백그라운드 이미지 적용시 아래 3가지를 기본으로 설정하게 됨.
    - background-image: url("");
    - background-size: 
    - background-position:
9. hover 효과주기, 다듬기
  식별자:hover{}
    - 마우스를 가져다 댔을 때 변경 적용
10. 마우스를 가져다 댔을 때 해당 동물명이 흰색 글자로 나타나게 할 것
  원리: 흰 글씨가 처음부터 있었음


2일차 

강의자료
https://www.notion.so/2-8f47e14182904060b19543b51f672aa2#6d9777f4abec494c9f98788f9ef782d9

1. 운세페이지 만들기
  빈 result.html을 만들고 index.html와 연결
2. 르탄이만들기
  index.html에서 코드 재활용. 결과페이지 이기 때문에 a태그를 div 태그로 바꿔야함.
3. 메세지 만들기
  h1태그와 p태그와 br태그 사용
4. 버튼 만들기
  div태그 안에 button태그 2개를 묶어주고 버튼의 중앙 정렬은 flex 사용.
  flex 사용시 - `display:flex` / - `flex-direction:row` / - `justify-content:center` 3가지 한번 더 기억할 것.
5. 모바일 버전 처리하기
  @media screen and (max-width: OOpx){
    body {
      background-color: green;
    }
  } 
    - 화면이 OOpx 이하 사이즈일 때 배경화면을 green으로 바꾸라는 의미.
    - 배경 적용 / 캐릭터 여백 조정 / p태그 글자 조정 / br태그 무시
6. 간단한 javascript 맛보기
  자바스크립트로 function 함수를 만들어 onclick 상황일 때 동작하게 만들기
7. 마지막 - 띠 별 메시지 만들기
  msg 클래스를 모두 가렸다가 띠에 맞는 문구만 보이게 코딩.
  그럼 만들어둔 2개의 페이지로 12개의 띠별 페이지가 다 따로 있는 것 같은 효과를 나타낼 수 있음.
8. 공유를 위한 기초작업
  og:image / og:title / og:description
  파비콘
9. 배포
  
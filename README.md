# FEproject

## 1. 목표

### 1.1 목표

- 페이지 자체의 목표 및 기능 없어 해당 프로젝트의 목표 작성

- html, css, javascript 사용법 익히기
- github 사용
- readme.md 작성법 익히기

### 1.2 팀 구성

- 박희주


## 2. 개발 환경

- HTML
- CSS
- JavaScript
- GitHub


## 3. 요구사항 명세와 기능 명세

[요구사항 명세와 기능 명세] https://github.com/gmlwn77/project1/blob/main/readme_img/%E1%84%8B%E1%85%AD%E1%84%80%E1%85%AE%E1%84%89%E1%85%A1%E1%84%92%E1%85%A1%E1%86%BC%E1%84%86%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A6.png

## 4. 프로젝트 구조와 개발 일정

### 4.1 프로젝트 구조

📂 project1
  
  ├──📂 img
  
  ├──📄 index.html 
  
  ├──📄menu.html
  
  ├──📄 mobile.html
  
  ├──📄 modal.html
  
  ├──📄 modal_mobile.html
  
  └──📄 reset.css
  

### 4.2 개발 일정 (WBS)

[개발일정] (https://github.com/gmlwn77/project1/blob/main/readme_img/%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%BC.png)

## 5. 역할 분담

- 팀장: 박희주
- FE: 박희주

## 6. 와이어프레임 / UI / BM

### 6.1 와이어프레임

[와이어프레임] (https://github.com/gmlwn77/project1/blob/main/readme_img/%E1%84%8B%E1%85%AA%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%A5%E1%84%91%E1%85%B3%E1%84%85%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%B7.png)

### 6.2 화면 설계

|index.html 1|index.html 2|
|------|---|
|[index.html 1](https://github.com/gmlwn77/project1/blob/main/readme_img/index1.png)|[index.html 2](https://github.com/gmlwn77/project1/blob/main/readme_img/index2.png)|
|modal 창|mobile 1|
|------|---|
|[modal 창](https://github.com/gmlwn77/project1/blob/main/readme_img/modal.png)|[mobile 1](https://github.com/gmlwn77/project1/blob/main/readme_img/mobile1.png)|
|mobile 2|mobile 3|
|------|---|
|[mobile 2](https://github.com/gmlwn77/project1/blob/main/readme_img/mobile2.png)|[mobile 3](https://github.com/gmlwn77/project1/blob/main/readme_img/mobile3.png)|
|mobile - modal|menu|
|------|---|
|[mobile - modal](https://github.com/gmlwn77/project1/blob/main/readme_img/mobile-modal.png)|[menu](https://github.com/gmlwn77/project1/blob/main/readme_img/menu.png)|

## 7. 메인 기능

- email 입력 후 subscribe 버튼 클릭 시 이메일 유효성 검사
    검사 통과 실패하면 email 재입력 필요
    검사 통과하면 모달창 생성되며, Ok! I LOVE BELL 클릭해서 데이터 전송 후 모달창 제거
  [모달 기능] https://github.com/gmlwn77/project1/blob/main/readme_img/%E1%84%86%E1%85%A9%E1%84%83%E1%85%A1%E1%86%AF%20%E1%84%80%E1%85%B5%E1%84%82%E1%85%B3%E1%86%BC.png

## 8. 에러와 에러 해결
  
- 스크롤 생성 과정에서 자바스크립트 사용 시 오류
    Uncaught ReferenceError: $ is not defined 오류 발생
  
    → 아래 명령어로 jquery import하여 오류 해결

    `<script src="https://code.jquery.com/jquery-3.4.1.js"></script>`
  
    참고 자료: https://wakestand.tistory.com/702

    
- input 으로 text를 입력받고 자바스크립트를 통해 키에 저장된 값을 가져올 때 input에 id 지정을 해야된다.
    
    ```jsx
    <input name="email" id="email" type="email" placeholder="Enter your e-mail address" required/>
    const email = *localStorage*.getItem('email');
    ```

## 9. 개발하며 느낀점

- html/css 사용이 익숙하지 않아 더 깔끔한 코드를 만들지 못한 것 같아 아쉽습니다.
- javascript를 활용해서 다양한 기능을 가능하게 한다는 점이 흥미로웠습니다.

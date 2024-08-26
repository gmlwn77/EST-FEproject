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

<img width="1025" alt="요구사항명세" src="https://github.com/user-attachments/assets/d801b326-0f18-4fbe-b36d-c3e49575f252">

## 4. 프로젝트 구조와 개발 일정

### 4.1 프로젝트 구조

📂 project1

  ├──📂 img
  
  ├──📂 readme_img
  
  ├──📄 index.html 
  
  ├──📄menu.html
  
  ├──📄 mobile.html
  
  ├──📄 modal.html
  
  ├──📄 modal_mobile.html
  
  └──📄 reset.css
  

### 4.2 개발 일정 (WBS)

<img width="1381" alt="개발일정" src="https://github.com/user-attachments/assets/bdea366b-b93a-433a-a384-b0315f892b7c">

## 5. 역할 분담

- 팀장: 박희주
- FE: 박희주

## 6. 와이어프레임 / UI / BM

### 6.1 와이어프레임

<img width="476" alt="와이어프레임" src="https://github.com/user-attachments/assets/c2c5afce-0b21-45b8-ab87-90341042960e">

### 6.2 화면 설계

|index.html 1|index.html 2|
|:------:|:---:|
|<img width="479" alt="index1" src="https://github.com/user-attachments/assets/2279bd97-a837-441f-9142-c2db892c7602">|<img width="479" alt="index2" src="https://github.com/user-attachments/assets/8b056574-7ddb-4085-889b-0a6169cb4185">|
|modal 창|mobile 1|
|<img width="432" alt="modal" src="https://github.com/user-attachments/assets/c912439a-0808-4fca-a314-ac6ccd93cae6">|<img width="194" alt="mobile1" src="https://github.com/user-attachments/assets/9c2cee1d-bfb1-4a61-8b72-baa73e37c731">|
|mobile 2|mobile 3|
|<img width="132" alt="mobile2" src="https://github.com/user-attachments/assets/a0ac04f8-9eb0-4419-b98f-200b979c47ce">|<img width="132" alt="mobile3" src="https://github.com/user-attachments/assets/ba691b6d-d0c4-4079-8f98-f5df50359efe">|
|mobile - modal|menu|
|<img width="418" alt="mobile-modal" src="https://github.com/user-attachments/assets/30a81a37-1098-49d1-b2e2-7dc043205abd">|<img width="293" alt="menu" src="https://github.com/user-attachments/assets/cc88cad1-4d4e-4b22-b353-a61839e844bb">|

## 7. 메인 기능

- email 입력 후 subscribe 버튼 클릭 시 이메일 유효성 검사
    검사 통과 실패하면 email 재입력 필요
    검사 통과하면 모달창 생성되며, Ok! I LOVE BELL 클릭해서 데이터 전송 후 모달창 제거
  
  <img width="236" alt="모달 기능" src="https://github.com/user-attachments/assets/bd5bd526-5aa2-4b5c-879f-0b0470a1e75c">

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

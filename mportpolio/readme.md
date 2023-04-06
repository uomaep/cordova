jquery mobile, cordova을 이용한 포트폴리오 앱

## 하드웨어 및 소프트웨어
<img width="392" alt="스크린샷 2023-03-31 오전 1 04 58" src="https://user-images.githubusercontent.com/114221785/228896845-31d67670-884c-4ac7-8c20-652844c19e98.png">
### 하드웨어
- 프로세서: 2.3 GHz 8코어 Intel Core i9
- 그래픽: AMD Radeon Pro 5500M 4 GB Intel UHD Graphics 630 1536 MB
- 메모리: 16GB 2667 MHz DDR4
### 소프트웨어
- 13.0.1(22A400)

## 결과
- 소개 페이지
<img width="425" alt="스크린샷 2023-03-26 오후 4 30 20" src="https://user-images.githubusercontent.com/114221785/227761761-8ffadeda-3105-4b2b-896c-74fd2a9b2d77.png">


- 인적 페이지
<img width="425" alt="스크린샷 2023-03-26 오후 4 29 06" src="https://user-images.githubusercontent.com/114221785/227761714-0277a198-c6c9-417d-a06c-64e7143d5df2.png">

- 경력 페이지
<img width="425" alt="스크린샷 2023-03-26 오후 4 29 26" src="https://user-images.githubusercontent.com/114221785/227761728-bae171b7-8067-4273-b617-eca2799dd69b.png">

- 학술 페이지
<img width="425" alt="스크린샷 2023-03-26 오후 4 29 26" src="https://user-images.githubusercontent.com/114221785/227761728-bae171b7-8067-4273-b617-eca2799dd69b.png">

## 라이브러리 
- jquery: 1.11.1
- jquery mobile: 1.4.5
- cordova: 11.1.0

## 코드
- 4개의 페이지를 한 개의 index.html 안에 다 넣음. data-role="page"
- 기존의 header를 jquery-mobile의 data-role="header"로 변경하여 모바일 화면에 맞게 수정
- 기존의 nav를 jquery-mobile의 data-role="navbar"로 변경하여 모바일 화면에 맞게 수정
- navbar를 header안으로 묶어 navbar도 header의 일부로 수정
- 기존의 footer를 jquery-mobile의 data-role="footer"로 변경하여 모바일 화면에 맞는 푸터로 수정
- footer의 position을 "fix"로 설정하여 content의 높이와 상관없이 푸터는 화면 하단에 고정시킴.


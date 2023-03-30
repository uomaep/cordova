# 고급프로그래밍 - cordova 앱 프로젝트
- 앱 이름: Travel
- 설명: 여행가기 좋은 지역 소개하는 앱

## 하드웨어 및 소프트웨어
<img width="392" alt="스크린샷 2023-03-31 오전 1 04 58" src="https://user-images.githubusercontent.com/114221785/228896845-31d67670-884c-4ac7-8c20-652844c19e98.png">
### 하드웨어
- 프로세서: 2.3 GHz 8코어 Intel Core i9
- 그래픽: AMD Radeon Pro 5500M 4 GB Intel UHD Graphics 630 1536 MB
- 메모리: 16GB 2667 MHz DDR4
### 소프트웨어
- 13.0.1(22A400)

## 사용 프로그램, 플러그인 및 라이브러리
### 사용 프로그램
- Visual Studio Code
- Xcode
- Cordova
- intelliJ
- Spring

### 사용 플러그인
- cordova splash screen: ^6.0.2 (앱 실행 시 로딩화면 커스텀)

### 사용 라이브러리
- jquery: ^1.11.1
- jquery-mobile: ^1.4.5
- swiper: ^9.1.1 (슬라이더 라이브러리)
- tailwindcss: ^3.2.7 (css framework)
- chart: (js chart library)

## 실행 결과(스크린샷)
#### 실행
<img width="425" alt="스크린샷 2023-03-31 오전 12 58 19" src="https://user-images.githubusercontent.com/114221785/228899281-dbd116e6-68a0-4a9e-91e4-8e880d33b855.png">
- splash screen 플러그인의 기능으로 로딩 화면 커스텀

#### 첫페이지
<img width="425" alt="스크린샷 2023-03-31 오전 12 58 31" src="https://user-images.githubusercontent.com/114221785/228899596-8c8ada7b-2f32-41d5-9f59-f156c5d66265.png">
<img width="425" alt="스크린샷 2023-03-31 오전 12 58 48" src="https://user-images.githubusercontent.com/114221785/228899740-28542ad6-3d51-4e56-8dd1-df2ef222c2de.png">
- 슬라이드 기능으로 경주와 하동을 선택할 수 있다. 선택 후 밑에 화살표 버튼을 누르면 각 지역의 여행지를 소개하는 페이지로 이동한다.

#### 여행지 소개 페이지
<img width="425" alt="스크린샷 2023-03-31 오전 12 58 51" src="https://user-images.githubusercontent.com/114221785/228900052-f6f5649c-1add-434b-b217-89f389a7dad0.png">
<img width="425" alt="스크린샷 2023-03-31 오전 12 58 56" src="https://user-images.githubusercontent.com/114221785/228900104-375ed165-b894-4fc6-8e1c-d5cdf912cd56.png">
- 각 지역의 여행지 추천 페이지이다. 4초마다 슬라이드가 자동으로 넘어가고 또한 터치 드래그 시에도 슬라이드가 넘어간다.

#### 메뉴 버튼
<img width="425" alt="스크린샷 2023-03-31 오전 12 59 03" src="https://user-images.githubusercontent.com/114221785/228900425-667cd7e0-2f8d-4573-80a0-827b2afa9ed0.png">
<img width="425" alt="스크린샷 2023-03-31 오전 12 59 07" src="https://user-images.githubusercontent.com/114221785/228900509-c25067dc-2b7f-4498-b82d-63478fe655d8.png">
<img width="425" alt="스크린샷 2023-03-31 오전 12 59 11" src="https://user-images.githubusercontent.com/114221785/228900557-1191769c-1d06-482a-9344-6808b7a8c0d5.png">
- 메뉴 버튼을 누르면 메뉴 팝업 창이뜬다.
- 첫 번째 메뉴는 개발자의 소개창이 뜬다.
- 두 번째 메뉴는 경주의 Top 5 여행지를 차트로 표현하는 창이 뜬다.
- 메뉴 버튼을 다시 누를 시 팝업 창이 사라진다.

#### 서버와 연동
## intellij, Spring 
- Gradle - Kotlin
- Language - Kotlin
- Spring Boot: ^3.0.5

### 서버 연동 화면(intellij, Spring)
<img width="2032" alt="스크린샷 2023-03-31 오전 1 28 30" src="https://user-images.githubusercontent.com/114221785/228903192-25ab1047-7759-40e1-9595-56a32633b5bc.png">

### localhost:8080에 접속
<img width="1072" alt="스크린샷 2023-03-31 오전 1 28 49" src="https://user-images.githubusercontent.com/114221785/228904027-de98e705-6c94-4510-873a-c63775d7f6ec.png">


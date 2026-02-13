## <div id="wrap"> 줬을 때 footer까지 주기
* logo 작명할 때 이름, 숫자 지우기 
* 클래스 이름 


## 코닥웹사이트 코딩 모든 과정 및 순서
1. html 5 입력
2. lang="ko" 언어 변경 / `<link rel="shortcut icon" href="./images/kodak_logo.png" type="image/x-icon">`
favicon(=favorite icon) : 웹사이트 제목표시줄에 있는 아이콘 표시-주로 로고 이미지를 삽입
3. `<link rel="stylesheet" href="./styles/reset.css">` / `<link rel="stylesheet" href="./styles/index.css">`
css 초기화 및 인덱스 css설정 - link rel = 수단을 의미 / href= 경로 
4. `<title>kodak | kodak apparrel online store</title>` 타이틀에 있는 제목을 써준다. 제목 형식은 코닥 | 코닥 어패럴로 구성 
5. html은 html head body로 구성 / head 설정 후 body에 페이지 전체를 감싸주는 <div id="wrap">를 작성한다. 
6. wrap 구성은 일반적으로 `header main footer`로 구성된다.
7. wrap 밑으로 `header 태그`를 작성한다.
8. 코닥 사이트의 헤더부분을 보면 `광고 문구 배너` / `브랜드 로고, gnb, 아이콘 묶음(검색, 마이페이지, 쇼핑) 으로 구성된다.
9. 광고문구를 보면 `설 연휴 10만원 쇼핑 지원금 받기!`를 클릭하면 다른 페이지로 넘어가는 것을 볼 수 있다. 

## 광고문구~메뉴바 구성
* <a href="#"><p>설 연휴 10만원 쇼핑 지원금 받기!</p></a>
* <h1><a href=""><img src="./images/kodak_logo.png" alt="Kodak"></a></h1> <!-- 브랜드로고를 h1으로 표시 -->
* 
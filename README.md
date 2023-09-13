# 팀 과제 - 영화 소개 앱 만들기
 - 스나이퍼팩토리 프론트엔드 프로젝트 부트캠프에서 만든 영화 만들기 팀프로젝트

<br>
[Github 배포링크](https://definitely92.github.io/movieAppList)

<br>

## 1. 로딩
- react-spinners를 이용하여 로딩화면 스타일을 구현

<br>

## 2. state
 - redux-toolkit 의 createSlice를 활용하여 좋아요 버튼을 눌렀을때 좋아요를 누른 영화리스트들을 따로 볼수 있게 구현.

<br>

## 3. 커스텀 hook
커스텀 훅을 사용하여 좋아요를 누른 영화목록, 영화 검색, 리스트 페이지 네이션, fetch  로직 등을 다양한곳에 사용할 수 있도록 따로 로직을 만듬.

<br>

## 4. context
여러 컴포넌트들에서 사용하는 state를 props로 내려주는 복잡한 방식이 아닌 편리하게 state를 전달 하는 context를 사용하여 좋아하는 영화들을 다양한 컴포넌트들에서 활용 가능하게 하였음.

<br>

## 5 . module.css
컴포넌트를 스타일링 할때 css클래스가 중첩되는 불편함을 줄이고 클래스 이름을 만드는 시간을 줄이기 위해서 사용.

<br>




### 🔔 화면 
**초기 화면**
![movieapp3](https://github.com/udemy-project-camp-team2/react-team-project-22/assets/132203871/a59cd71b-20bf-4610-9c05-f1d20d9e99b6)

**검색**
![movieapp2](https://github.com/udemy-project-camp-team2/react-team-project-22/assets/132203871/47b88f51-d00e-4c64-9712-3cb79f4b7094)
영화 이름 검색

**좋아하는 영화 리스트 추가 삭제**
![movieapp1](https://github.com/udemy-project-camp-team2/react-team-project-22/assets/132203871/6c78fbca-c34b-4d22-920e-ffc0d8dab1ae)
좋아요 클릭시 좋아하는 영화 리스트로 이동

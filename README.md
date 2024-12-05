### 🐭 Pandas in Action (판다스 인 액션)

---
<img src="https://image.yes24.com/goods/112208378/XL.jpg" alt="Book" style="width: 200px; display: block; margin-left: auto; margin-right: auto;">


---
### ✅ 소개
    @ 이 저장소는 "판다스 인 액션(Pandas in Action)" 도서를 학습하며 작성한 실습 코드와 예제를 정리한 자료입니다.
    @ 책의 내용을 직접 구현하고 확장하면서 학습한 내용을 기록하고 공유하기 위해 제작되었습니다.


---
### ✅ 목차
1. [✅ 개발 환경](#개발-환경)
2. [✅ 디렉토리 구성](#디렉토리-구성)
3. [✅ 실행 방법](#실행-방법)


---
<a name="개발-환경"></a>
#### 🙈 개발 환경
	- PC : MacBook Air 2020 M1 chip
	- macOS : Sequoia 15.0.1
	- Safari 18.0.1 (Jupyter Notebook)
	- 라이브러리 : requirements.txt


---
<a name="디렉토리-구성"></a>
#### 🗄️ 디렉토리 구성
```sh
├─Pandas_in_Action (판다스 인 액션)
│  └─1장. 판다스 소개
│  │  ├─Jupyter Notebook
│  │  │      1장. 판다스 소개.ipynb
│  │  ├─Datasets
│  │  │      movies.csv
│  └─2장. Series 객체
│  │  ├─Jupyter Notebook
│  │  │      2장. Series 객체.ipynb
│  │  │      2장. Series 객체 연습문제.ipynb
│  └─3장. Series 메서드
│  │  ├─Jupyter Notebook
│  │  │      3장. Series 메서드.ipynb
│  │  │      3장. Series 메서드 연습문제.ipynb
│  │  ├─Datasets
│  │  │      pokemon.csv
│  │  │      revolutionary_war.csv
│  │  │      google_stocks.csv
│  └─4장. DataFrame 객체
│  │  ├─Jupyter Notebook
│  │  │      4장. DataFrame 객체.ipynb
│  │  │      4장. DataFrame 객체 연습문제.ipynb
│  │  ├─Datasets
│  │  │      nba.csv
│  │  │      nfl.csv
│  └─5장. DataFrame 필터링
│  │  ├─Jupyter Notebook
│  │  │      5장. DataFrame 필터링.ipynb
│  │  │      5장. DataFrame 필터링 연습문제.ipynb
│  │  ├─Datasets
│  │  │      employees.csv
│  │  │      netflix.csv
│  └─6장. 텍스트 데이터 다루기
│  │  ├─Jupyter Notebook
│  │  │      6장. 텍스트 데이터 다루기.ipynb
│  │  │      6장. 텍스트 데이터 다루기 연습문제.ipynb
│  │  ├─Datasets
│  │  │      chicago_food_inspections.csv
│  │  │      customers.csv
│  └─7장. MultiIndex DataFrame
│  │  ├─Jupyter Notebook
│  │  │      7장. MultiIndex DataFrame.ipynb
│  │  │      7장. MultiIndex DataFrame 연습문제.ipynb
│  │  ├─Datasets
│  │  │      investments.csv
│  │  │      neighborhoods.csv
│  └─8장. 재구성과 피벗
│  │  ├─Jupyter Notebook
│  │  │      8장. 재구성과 피벗.ipynb
│  │  │      8장. 재구성과 피벗 연습문제.ipynb
│  │  ├─Datasets
│  │  │      used_cars.csv
│  │  │      video_game_sales.csv
│  │  │      minimum_wages.csv
│  │  │      recipes.csv
│  │  │      sales_by_employee.csv
│  └─9장. GroupBy 객체
│  │  ├─Jupyter Notebook
│  │  │      9장. GroupBy 객체.ipynb
│  │  │      9장. GroupBy 객체 연습문제.ipynb
│  │  ├─Datasets
│  │  │      cereals.csv
│  │  │      fortune1000.csv
│  └─10장. 병합, 조인 및 연결
│  │  ├─Jupyter Notebook
│  │  │      10장. 병합, 조인 및 연결.ipynb
│  │  │      10장. 병합, 조인 및 연결 연습문제.ipynb
│  │  ├─Datasets
│  │  │  ├─meetup
│  │  │  │   categories.csv
│  │  │  │   cities.csv
│  │  │  │   groups1.csv
│  │  │  │   groups2.csv
│  │  │  ├─restaurant
│  │  │  │   customers.csv
│  │  │  │   foods.csv
│  │  │  │   week_1_sales.csv
│  │  │  │   week_1_satisfaction.csv
│  │  │  │   week_2_sales.csv
│  └─11장. 날짜 및 시간 다루기
│  │  ├─Jupyter Notebook
│  │  │      11장. 날짜 및 시간 다루기.ipynb
│  │  │      11장. 날짜 및 시간 다루기 연습문제.ipynb
│  │  ├─Datasets
│  │  │      citibike.csv
│  │  │      deliveries.csv
│  │  │      disney.csv
│  └─12장. 가져오기와 보내기
│  │  ├─Jupyter Notebook
│  │  │      12장. 가져오기와 보내기.ipynb
│  │  │      12장. 가져오기와 보내기 연습문제.ipynb
│  │  ├─Datasets (.xlsx)
│  │  │      Baby_Names.xlsx
│  │  │      Multiple Worksheets.xlsx
│  │  │      Single Worksheets.xlsx
│  │  │      tv_show.xlsx
│  │  ├─Datasets (.json)
│  │  │      nobel.json
│  │  │      tv_show.json
│  │  ├─Datasets (.csvv)
│  │  │      NYC_Baby_Names.csv
│  └─13장. 판다스 설정
│  │  ├─Datasets
│  │  │      happiness.csv
│  └─14장. 시각화
│  │  ├─Jupyter Notebook
│  │  │      14장. 시각화.ipynb
│  │  ├─Datasets
│  │  │      space_missions.csv
│────requirements.txt
└────README.MD
```

---
<a name="실행-방법"></a>
### ✅ 실행 방법
1. Terminal 열기
2. 디렉토리 생성:
    ```bash
    mkdir "Git 파일"
3. 저장소 클론:
    ```bash
    git https://github.com/Moomin03/Pandas_in_Action
4. 디렉토리 이동

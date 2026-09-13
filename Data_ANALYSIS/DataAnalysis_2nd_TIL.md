# 데이터분석 2주차 정규과제

📌데이터분석 정규과제는 매주 정해진 분량의 『*혼자 공부하는 데이터 분석 with 파이썬*』 을 읽고 학습하는 것입니다. 이번 주는 아래의 **DataAnalysis_2nd_TIL**에 나열된 분량을 읽고 공부하시면 됩니다.

아래의 문제를 풀어보며 학습 내용을 점검하세요. 문제를 해결하는 과정에서 개념을 스스로 정리하고, 필요한 경우 제시된 강의를 참고하여 보완하는 것이 좋습니다.

<!-- 강의 링크는 아래와 같습니다.
https://www.youtube.com/watch?v=s_-VvTLb3gs&list=PLVsNizTWUw7FGzSRCkQrPEEe-ljVXgS7k&index=4
https://www.youtube.com/watch?v=Il6L8OtNFpc&list=PLVsNizTWUw7FGzSRCkQrPEEe-ljVXgS7k&index=5
-->


## DataAnalysis_2nd_TIL

### 2장 데이터 수집하기
#### 01. API 사용하기
#### 02. 웹 스크래핑 사용하기


## Study Schedule

| 주차  | 공부 범위     | 완료 여부 |
| ----- | ------------- | --------- |
| 1주차 | p.24~81    | ✅         |
| 2주차 | p.84~151   | ✅         |
| 3주차 | p.154~219  | 🍽️         |
| 4주차 | p.222~279 | 🍽️         |
| 5주차 | p.282~325 | 🍽️         |
| 6주차 | p.328~379 | 🍽️         |
| 7주차 | p.382~430 | 🍽️         |

<br>

<!-- 여기까진 그대로 둬 주세요-->


# 1️⃣ 개념 정리 

## 01. API 사용하기


### API

두 프로그램이 서로 대화하기 위한 방법을 정의한 것

* **HTTP** - 인터넷에서 웹 페이지를 전송하는 기본 통신 방법
* **HTML** - 웹 브라우저가 화면에 표시할 수 있는 문서의 한 종류이자 웹 페이지를 위한 표준 언어

### 웹 기반 API

CSV, JSON, XML 형태의 데이터를 전달

### JSON

* 딕셔너리 + 리스트 형태
* 파이썬에서 쉽게 파싱 가능 (`.json()`)
* 가독성이 좋고 가볍다

### XML

* 엘리먼트들이 계층구조를 가짐
* 태그로 데이터를 감싸서 표현
* 구조가 명확하지만 JSON보다 무겁다


## 02.웹 스크래핑 사용하기


### 웹 스크래핑

프로그램으로 웹사이트의 페이지를 옮겨 가면서 데이터를 추출하는 작업

### 뷰티풀수프 (BeautifulSoup)

HTML 안에 있는 내용을 찾을 때 사용하는 파이썬 라이브러리

### 주의점

* 웹사이트에서 스크래핑을 허락하였는지 확인 (robots.txt, 이용약관 확인)
* HTML 태그를 특정할 수 있는지 확인 (개발자도구 사용)
* API 이용약관 준수


# 2️⃣ 수행 인증

![alt text](image/image-3.png)
![alt text](image/image-4.png)
![alt text](image/image-5.png)
![alt text](image/image-6.png)
![alt text](image/image-7.png)
<br>
<br>

# 3️⃣ 확인 문제

## 문제 1.

> **🧚Q. 다음 중 BeautifulSoup 외에 웹 스크래핑에 사용할 수 있는 파이썬 패키지로 가장 적절한 것은 무엇인가요?**

```
1️⃣ NumPy  
2️⃣ Scrapy  
3️⃣ Matplotlib  
4️⃣ Scikit-learn  
```

```
2️⃣ Scrapy

이유:
Scrapy는 웹 스크래핑 전용 프레임워크로, BeautifulSoup과 마찬가지로 HTML을 파싱하여 데이터를 추출할 수 있습니다. 대규모 웹 크롤링 프로젝트에 더 적합한 구조를 제공한다.
```



### 🎉 수고하셨습니다.
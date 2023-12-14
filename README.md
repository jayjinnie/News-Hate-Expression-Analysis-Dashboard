# 2022년 정보사회미디어학과 데이터 사이언스 학회 DAYS 발표행사 Data Visualization Festival (D.V.F.) <br> 뉴스 플랫폼 혐오표현 분석 비즈니스 대시보드 구축 프로젝트

<div align="center">
  
![image](https://github.com/jayjinnie/News-Hate-Expression-Analysis-Dashboard/assets/65335952/7df045b1-0c2d-48f6-b223-3debd2d93a4c)
</div>

## 프로젝트 개요
* **작업 기간**<br>
  2022.11.26 ~ 2022.11.30
* **분석 데이터** <br>
  * <a href="https://github.com/kocohub/korean-hate-speech">Kocohub 한국어 혐오표현 말뭉치 데이터셋</a>
  * <a href="https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=SocialMedia.csv">Real World Fake Data</a>
* **분석 목적** <br>
  인터넷 상 혐오 표현의 증가로 인한 여러 사회 문제 현상을 방지하기 위해, KISO(한국 인터넷 자율 정책 기구)를 타겟팅하여 뉴스 댓글을 모니터링하며 혐오 표현 확산 방지를 위한 솔루션을 제고하고, 복수의 뉴스 플랫폼을 효율적으로 매니징할 수 있는 비즈니스 대시보드를 구축한다.
* **분석 환경** <br>
  Python, PyTorch

<br>

## 프로젝트 내용
HuggingFace에서 제공하는 Pretrained BERT 모델을 활용하여 입력된 뉴스 댓글에 대한 혐오 표현을 분류해내는 Multi Label Classification Task를 구현하였다. <br> 각 댓글의 혐오 지수를 계산하기 위한 식으로 LRAP(abel Ranking Average Precision)을 사용하였다. <br> KISO의 비즈니스 목표 및 방향성을 기반으로, 혐오 댓글 모니터링을 위한 니즈를 정의하여 대시보드를 스케칭하고, 인터랙티브 대시보드를 구현하였다.
<div align="center">
  
https://github.com/jayjinnie/News-Hate-Expression-Analysis-Dashboard/assets/65335952/4f6b6d63-2d24-4d1d-a74b-6b15c267c920
</div>

<br>

## 프로젝트 성과
**DAYS 연말 발표 행사 D.V.F. 성황리에 마무리, 총 17명의 수료생 탄생🎉**
<div align="center">

![dvf](https://github.com/jayjinnie/News-Hate-Expression-Analysis-Dashboard/assets/65335952/ce1e03f3-4847-4a93-ade3-f0b98d5566e4)
</div>

<br><br><br>
---
### DAYS 학회 활동 연혁
* **<a href="https://www.instagram.com/_hy_days/">DAYS 공식 SNS</a>**
* **2020년 신입 기수 가입**
  * <a href="https://youtu.be/fTc69YlWqmI?si=sKY9BZS6pUSxPm8Q&t=38">개인프로젝트 '서울시 인구 수와 CCTV 수 간의 상관관계 분석'</a>
* **2021년 운영진 활동**
  * <a href="https://youtu.be/Zs4oLQVqBdQ?si=ES1AYjrdyE09QzcV">신입생 대상 Python 기초 강의 진행</a>
  * <a href="https://youtu.be/h5iMyrcT7ho?si=Uo0rBLmth42z5dIZ">학과 대상 Python 웹 스크래핑(BeautifulSoup, Selenium) 툴 스터디 강의 진행</a>
  * 정보사회미디어학과 학술제 CONNECTION 2팀 팀장 <a href="https://youtu.be/RRvyVsyt1Ro?si=XAJ_0FAF0ZsDTBHr">"데이터로 보는 OTT서비스의 지속 가능성 탐색 프로젝트"<a>
* **2022년 학회장 활동**
  * 학회 교육 커리큘럼 전면 개편, <a href="https://days-hanyang-erica.netlify.app/">학회 홈페이지</a> 구축
  * 1학기 Python 데이터 분석 프로젝트 발표 행사 <mark>'Python Wrap-Up Project'</mark> 성료
  * 2학기 Tableau 데이터 시각화 프로젝트 발표 행사 <mark>'Data Visualization Festival(D.V.F.)'</mark> 성료

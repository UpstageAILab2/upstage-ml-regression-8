![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)
# Upstage AI Lab ML Competition

## Team

<table>
<tr>
<td> <div align=center> 팀장 </div> </td>
<td> <div align=center> 팀원</div> </td>
<td> <div align=center> 팀원</div> </td>
<td> <div align=center> 팀원</div> </td>
</tr>
<tr>
<td> <div align=center> <b>정소미</b> </div> </td>
<td> <div align=center> <b>임승환</b> </div> </td>
<td> <div align=center> <b>최용빈</b> </div> </td>
<td> <div align=center> <b>김종완</b> </div> </td>
</tr>
<tr>
<td> <img alt="Github" src="https://i.ibb.co/yydQ7j8/image.png" width="150" height="150"/> </td>
<td> <img alt="Github" src="https://i.ibb.co/KF0w5S0/image.png" width="150" height="150"/> </td>
<td> <img alt="Github" src="https://i.ibb.co/drKyHYz/image.png" width="150" height="150"/> </td>
<td> <img alt="Github" src="https://avatars.githubusercontent.com/u/156163982?v=4" width="150" height="150"/> </td>
</tr>
<tr>
<td> <div align=center> <a href="https://github.com/sommizzu"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </a></div> </td>
<td> <div align=center> <a href="https://github.com/LimSH0731"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </a></div> </td>
<td> <div align=center> <a href="https://github.com/whybe-choi"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </a></div> </td>
<td> <div align=center> <a href="https://github.com/"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </a></div> </td>
</tr>
</table>

## 1. Competition Info

### Overview

<img width="398" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/63583ace-ed20-4d82-8fb7-9d3238eeb4a3">


### Timeline
![Timeline](https://github.com/sommizzu/sommizzu/assets/79901950/868063b3-5cde-4a4b-a6ce-75fd6635b309)

### Evaluation

- RMSE 지표를 활용

<img width="216" alt="Evaluation" src="https://github.com/sommizzu/sommizzu/assets/79901950/c236415c-53b2-439b-a711-e9845b67ba16">

## Data structure

### Directory
```python
project/
│
├── src/            # Figures & plots
│
├── data/           # Dataset
│
├── collection/     # Data collection & preprocessing scripts
│
├── model/          # Model tuning & training code
│
├── docs/           # Project reports & documentation
│
└── README.md       # Project overview
```

## Data description

### Dataset overview

- 학습 데이터 (2007.01.01 ~ 2023.06.30)
 1,118,822개 거래 데이터
 52개 변수 (거래금액 포함)

- 평가 데이터 (2023.07.01 ~ 2023.09.26)
 9,272개 거래 데이터
 51개 변수 (거래금액 제외)

- 지하철역 데이터<br/>
 서울시 지하철역 정보
 역사명, 호선, 역의 X좌표, Y좌표

- 버스정류장 데이터<br/>
 서울시 버스 정류소 정보
 정류소번호, 정류소명, 정류소의 X좌표, Y좌표


## EDA

<img width="529" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/bbbfe0dc-d5fb-4298-9a2f-d1e614d8e2f3">

<img width="532" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/b3dde2a4-87ec-4412-a883-c37b835d1cdb">

## Modeling

### Model I
<img width="533" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/9e90ceed-72f1-4298-a38a-4b39cbabc290">

<img width="534" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/2e4d609f-f4ca-4924-9f15-ebd06d16b035">

### Model II

<img width="532" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/7283fbe6-afa6-484d-87cf-3709d83b80af">

<img width="532" alt="image" src="https://github.com/sommizzu/Blind_crossWalk/assets/79901950/4bded75a-e619-4dfc-aed4-3f53928350f5">

## Result

### Leader Board

<img width="859" alt="Leaderboard 1" src="https://github.com/sommizzu/sommizzu/assets/79901950/35343320-c960-414f-98aa-fe56906adcfa">

<img width="882" alt="Leaderboard 2" src="https://github.com/sommizzu/sommizzu/assets/79901950/22a1b844-7298-44b0-9f49-32f948b2943b">

### Presentation

- [8조 PPT](https://docs.google.com/presentation/d/1O1rWaK0lRSIgCDd-hAbgYT5mkAo6NAZl-SdDk_E3ctU/edit?usp=sharing)

## Reference

- [서울시 역사마스터 정보](https://data.seoul.go.kr/dataList/OA-21232/S/1/datasetView.do)
- [직방(호갱노노)](https://hogangnono.com/)
- [네이버부동산](https://land.naver.com/)
- [서울시 개별공시지가 정보](https://data.seoul.go.kr/dataList/OA-1180/F/1/datasetView.do)
- [서울시 공동주택 아파트 정보](https://data.seoul.go.kr/dataList/OA-15818/S/1/datasetView.do)

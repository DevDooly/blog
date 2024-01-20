---
title: ETF Tracer] Initialize
# date: 2024-01-20 10:39:00 +0900
categories: [ToyProject, ETF Tracker]
tags: [ToyProject, ETF Tracker]
---
Target ETF 의 투자리스트 및 각 종목별 등락률 조회

조회된 데이터를 보여주는 방식은 아래와 같다.

* 기간 : 1일 / 1주 / 1월 / 1년 / 5년 / 전체
* 출력 형식  
  * 등락률 % 출력 (기본) : {등락률}% 로 출력
  * 기간내 등락률 출력 : 선 그래프 형식으로 기간 내 등락률 출력
* 출력은 모두 리스트로 출력한다


## 개발환경
* Front-End : React.Js
* Back-End : Spring Boot
* DB : H2 DB

## 생각 정리
* 출력형식에 기간 내 가장 상승률 높은 3개만 보여주는 기능 추가할지. 
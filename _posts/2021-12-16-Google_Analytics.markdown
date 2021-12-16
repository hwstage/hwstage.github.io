---
layout: post
title:  "Google Analytics"
date:   2021-12-16
description : About Analytics
comments: true
---
# Google Analytics
## Google Analytics란?
구글에서 무료로 제공하는 **웹분석** 서비스

## Github page와 Google Analytics 연동

1. Google Analytics 속성 생성
2. Gitpage의 _config.yml 수정하기


## 1. GoogleAnalytics 속성 생성하기
우선 GoogleAnalytics의 계정을 만든다.  
Google 계정과 **별도**이므로 없다면 생성해줘야한다.  

1. 속성 열에서 속성 만들기 선택
2. 속성 이름, 시간대, 통화 선택

### 추적 아이디 설정 !  
추적 아이디가 G-가 아닌 UA-가 필요하므로, 고급 옵션에서 유니버설 애널리틱스 속성 만들기 활성화!!  
웹사이트 URL에 Git Page 링크를 입력
비즈니스 규모, 사용 계획, 업종 선택하고 만들기  
추적 아이디는 데이터 스트림을 입력한 후 생성하면 얻을 수 있다.  

## 2. _config.yml 수정하기
Git page의 _config.yml 파일을 수정한다.  
google_analytics : "<UA-아이디>" 입력

# 연동 완료 !
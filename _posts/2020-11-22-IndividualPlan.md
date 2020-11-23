---
layout: post
title:  개인 참여 계획
date:   2020-11-22 15:11:22 +0300
---

```
현재 프로젝트에 사용된 crwaler module
python3 - scrapy
python3 - beautifulsoup
```

# 1. 이슈 관리

***특정 기사란의 크롤링이 안됨***   
네이버 기사 html을 parsing하여 원하는 정보를 scraping해오는데, 최근 네이버 UI가 변경되면서 parsing에 오류있음

***크롤링 칼럼 추가***   
현재 기사원문, 날짜, 언론사의 칼럼만을 scraping 해 온다. 독자들의 반응이나 피드백의 정보를 가져오는 api를 구현하기 위해 크롤링하는 칼럼을 추가 할 필요

11/23~   
Crawling execution time 같은 performance 측면에서 이슈를 찾아볼 예정

# 2. 코드 기여
***기능 수정 part***   
11/30   
일부 크롤링이 안되는 오류   
Selenium 모듈을 이용한 parsing메소드에 변경된 ui 적용   

***기능 추가 part***  
12/7   
네이버 뉴스 기사 댓글란 html 태그 분석   
분석 내용 바탕으로 크롤링 칼럼 추가   

# 3. 문서화 작업
12/1   
Readme에 변경된 method 내용 추가   
Readme 영문 문서 작업   

11/23 ~   
정적페이지에 활동내역 정리

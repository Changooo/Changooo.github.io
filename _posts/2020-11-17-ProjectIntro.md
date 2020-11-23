---
layout: post
title:  참여 프로젝트 소개
date:   2020-11-17 11:02:33 +0300
---

KoreaNewsCrawler
================
[Github](https://github.com/lumyjuwon/KoreaNewsCrawler)   
   
네이버 뉴스기사 크롤러(Python) 프로젝트 
----------------------------------------
Github Stars: 116
Lisence: Apache-2.0 License
<hr>   
네이버에서 제공하는 뉴스기사를 분야별로 스크래핑하여 기사내용, 언론사, 작성된 날짜들의 정보를 가져오는 프로젝트입니다. Python이 사용됐습니다. Github에 해당 프로젝트의 소스가 공개되어있고, 커뮤니티가 활발히 진행중입니다.    


## User Python Installation
* **KoreaNewsCrawler**

    ``` pip install KoreaNewsCrawler ```
## Method
* **set_category(category_name)**
  
 이 메서드는 수집하려고자 하는 카테고리는 설정하는 메서드입니다.  
 파라미터에 들어갈 수 있는 카테고리는 '정치', '경제', '사회', '생활문화', 'IT과학', '세계', '오피니언'입니다.  
 파라미터는 여러 개 들어갈 수 있습니다.  
 category_name: 정치, 경제, 사회, 생활문화, IT과학, 세계, 오피니언 or politics, economy, society, living_culture, IT_science, world, opinion
  
* **set_date_range(startyear, startmonth, endyear, endmonth)**
  
 이 메서드는 수집하려고자 하는 뉴스의 기간을 의미합니다. 기본적으로 startmonth월부터 endmonth월까지 데이터를 수집합니다.
  
* **start()**
  
 이 메서드는 크롤링 실행 메서드입니다.


## 참여방안  

# 코드 기여
1. 해당 Git repository를 fork/clone하여 프로젝트 관리
    + 지속적인 코드 리뷰 및 디버깅/업데이트를 pull request 하여 코드에 기여
    + 최근 네이버 기사 탭 UI의 변경으로 크롤러에 많은 업데이트가 필요할 것으로 예상
    + 작동안되는 크롤러 수정/새 기능이나 크롤링칼럼 추가, 2가지 type으로 진행
   
2. 문서화 작업
    + Github 페이지에 위키추가 ( 현재 wiki 문서 없음 )
    + Github 페이지에 readme 문서 업데이트 ( 현재 상황과 일치하지 않는 부분 있음 )
    + 각 문서 국/영문 번역 작업 ( 국내외 개발자들의 참여 유도 )
    + 정적페이지에 활동 내용 및 프로젝트 설명 작성

3. 이슈관리
    + Github Issue 탭에 버그리포트 작성 ( 버그 재현 방법 포함 ) 
    + 해당 프로젝트/커뮤니티 Watch
    + 새 기능 구상하여 Issue 탭에 Comment

4. 활동 모니터링
    + Github Insigts를 이용한 Contributors 관리


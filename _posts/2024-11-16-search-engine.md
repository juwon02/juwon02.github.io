---
title: "[Github blog] 검색엔진에 노출시켜보자"
excerpt: "Naver와 Google에 노출시켜보자!"

writer: Juwon02
categories:
    - Github blog
    - Tutorial
tags:
    - Blog
    - Github
    - Git
    - jekyll
pin: true
---
# Github Blog 검색엔진에 노출시키기
이제 블로그를 남들에게 보여주기 위한 첫걸음을 하겠습니다. 
## Naver
첫번째로 Naver입니다.
1. [Naver Search Advisor](https://searchadvisor.naver.com/) 접속하기
2. 네이버 로그인 후 이용약관 동의하기
3. 우측 상단위에 `웹마스터 도구` 클릭
4. 내 Github Blog URL을 입력하고 등록하기
5. HTML 태그 체크하기
6. 메타 태그 복사 후 `head.html` 경로에 들어가 다른 코드에 영향이 없는 곳에 붙여넣기
7. `소유하기` 클릭
8. 사이트맵 제출하기 요청->사이트맵 제출-> 사이트맵 URL 입력 ->확인

### Naver 끝
이렇게 해도 바로 검색되지 않고 Naver에서 확인 후 검색이 됩니다.

## Google
1. [Google Search Console](https://search.google.com/search-console/about)에 접속하기
2. Google 로그인
3. `시작하기` 클릭
4. 내 Github Blog URL을 입력한 후 `계속`  클릭
5. 소유권 확인에서 HTML 태그 클릭후 매타 태그 복사
6. `_config.yml`에서 webmaster_verification: 아래 google 찾기
7. 복사한 테그 안에서 content= 이후 " "안에 있는 내용 붙여넣기
8. 사이트맵 제출하기 요청->사이트맵 제출-> 사이트맵 URL 입력 ->확인

### Google 마무리
Naver와 마찬가지로 google에서 확인 후 검색이 가능합니다.
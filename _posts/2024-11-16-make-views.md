---
title: "[Github blog] 조회수를 확인할 수 있게 해보자"
excerpt: "GoatCounter를 이용해 조회수를 확인해보자!"

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
# Github Blog에 조회수 표시하기
이제 블로그에 조회수를 확인 할 수 있도록 해보자 조회수 카운터를 확인 할 수있는 GoatCounter 사용하기
## GoatCounter
1. [GoatCounter](https://www.goatcounter.com/signup)접속하기
2. `Sign up`
3. Code: 내가 갖고싶은 서브도메인주소를 쓰면 된다. (단 _언더바는 안된다)
4. site domain: 내 블로그 주소를 적으면 된다.
5. email address: 께정 검증용 이메일
6. password: 8자리만 채우면 된다.
7. Fill in 9 here : 9를 채우면 된다.


이 과정을 수행하면 내 서버를 가진 goatcounter사이트가 생성된다.
## Settings
- 우측 상단에 있는 settings을 누르고 들어가서 방문자가 조회수를 볼 수 있게 설정한다.
-`site settings`->`Allow adding visitor counts on your wevsite`클릭
- 아래 `save`누르기

## _config.yml 수정
내 _config.yml에 들어가 `analytics`에서 `goatcounter`에 회원가입 때 썼던 내코드(서브도메인)을 적는다.
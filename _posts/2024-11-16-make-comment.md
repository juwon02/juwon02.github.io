---
title: "[Github blog] 댓글을 달 수 있게 만들어보자"
excerpt: "UTTERANCES을 이용해 댓글을 달 수 있게 만들자!"

writer: Juwon02
categories:
    - Github blog
    - Tutorial
tags:
    - Blog
    - Github
    - Git
    - jekyll
---

# Github Blog에서 댓글을 달 수 있게 만들어보자

## 댓글 기능을 왜 만들어야 할까?
- 내가 쓴 게시물이 도움이 되었는지 확인이 가능하다
- 내가 틀린 곳이 있다면 수정을 통해 더 나은 방향을 제시 받을 수 있는 기회가 올 것이다.   

## UTTERANCES 적용하기
> Utterances무료로 댓글기능을 사용할 수 있게 해준다. 그것도 광고도 없이 가능하게 해준다.
## 1. 설치
- 먼저 Github App에서  [Utterances](https://github.com/apps/utterances)를 설치해야한다.
- 설치 페이지에서 접속하고 Install 버튼을 누르면 저장소를 선택할 수 있는 화면이 나온다.

## 2.설정
- 설치가 완료되면 설정 페이지로 이동한다. 설정페이지에서 
- repo에서 `계정명/저장소이름`을 입력하면 된다.
- Issue title contains page pathname 체크
- 이슈 라벨과 테마 설정도 할 수 있다.
## 3. Enable Utterances 설정하기
- 다 작성하면 Enable Utterances가 나오는데 이 코드박스 안에 `repo`와 `issue-term`부분만 적용할 것이다.
- _config.yml에서 comment: 부분을 착는다. 
- utterances" 아래 `repo`와 `issue-term`부분을 사이트에서 복사 붙여넣기를 한다.
## 4. 마지막
- `copy`를 버튼을 눌러 전체를 복사한다.
 - _layout/post.html로 들어간다.
 - 마지막 줄에 붙여넣기를 해준다.
 - 커밋 메세지 입력 후 커밋& 푸시


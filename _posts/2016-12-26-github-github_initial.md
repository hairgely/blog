---
layout: post
title: "[GitHub] 히스토리 초기화"
description: 
headline: 
modified: 2016-12-26
category: github
tags: [github]
imagefeature: 
mathjax: 
chart: 
comments: true
featured: true
---
몇일전 github에 DB 접속정보가 포함되서 push가 되었다. 외부에서 DB에 접근할수 있는 매우 중요한 정보이기 때문에 히스토리 까지 삭제할 필요가 있었다. 
 
물론 DB안에는 별다른 정보는 없다. ㅎㅎ 다만, 누군가가 내 DB에 접근할 수도 있다는 것이 찝찝할 뿐...

## GitHub 초기화
###히스토리 초기화하는 방법이다. 
 
1. rm -rf .git 
2. git init
3. git add . 
4. git commit -m "initial repository"
5. git remote add origin <github-url>
6. git push -u --force origin master

### 원본 블로그
* [조영's lab Dev_[GitHub] 히스토리 삭제하기(초기화하기)]( http://balhae79.tistory.com/358 )

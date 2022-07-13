---
title: Git and Github Pages
author: Jihyun Lee
date: 2022-07-12 15:40:00 +0800
categories: [Blogging, Git/Github]
tags: [git, github]
math: true
mermaid: true

# 내가 보려고 만든 git 명령어 모음집
___

## Git 명령어:
<!-- git init -->
git init:
* git 초기화
* .git 폴더 생성
```
git init
```

<!-- git status -->
git status:
* git 상태 확인
```
git status
```

* 수정된 file/staging area에 있는 file 확인
```
git status -s
```

<!-- git diff -->
git diff:
* 수정사항 상세 설명
```
git diff
```

<!-- git add -->
git add:
* working directory에 있는 모file을 staging area에 옮김
```
git add .
```

<!-- echo -->
ehco:
* file에 코드 추가
```
echo [코드] >> [파일명.확장자]
```

<!-- git commit -->
git commit:
* staging area에 있는 변경사항을 git repository에 이동
```
git commit -m "message"
```

## Github-Pages 명령어

github-pages 수정 시:
* 아래 명령어 모두 입력
```
cd /Users/jihyun/Desktop/IdeaProjects/Jihyun3478.github.io
git add .
git commit –m "message"
git push
bundle exec jekyll serve
```

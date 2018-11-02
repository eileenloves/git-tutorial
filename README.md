# Git tutorial M43B

## zzu.li/m43b

## Getting started

# Learn Git

## What is Git?

VCS(Version Control System) /SCM(Source Code Manager)

git은 버전관리를 한다.  gitHub랑은 다르다!

| Command            | Description                      | Example      |
| ------------------ | -------------------------------- | ------------ |
| `$ git config --global user.name "name"`   | git에서 사용할 이름을 설정 [최초 1회]          |
| `$ git config --global user.email "email"` | github 주소에서 사용하는 메일을 설정 [최초1회] |
| `$ git init`                               | .git 디렉토리 생성 및 초기화                   |
| `$ rm -rf .git`                            | .git 디렉토리 삭제                             |
| `$ git add remote "git repository url"`    | 리모트 repository를 가리킨다.                  |
| `$ git status`                             | 현재 git 상태를 확인                           |
| `$ git add <FILE> or <PATH>`               | <FILE> or <PATH>을 트랙 및 스테이징한다.       |
| `$ git commit -m "등록할 메세지"`          | 트랙 및 스테이징한 목록을 commit한다.          |
| `$ git log`                                | commit한 list를 본다.                          |
| `$ git push -u origin master`              | commit한 list를 push [최초 1회]                |
| `$ git diff`                               | 파일의 수정된 정보를 확인한다.                 |
| `$ git commit --amend`                     | 마지막 commit 정보를 editor로 open             |

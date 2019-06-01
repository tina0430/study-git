# Hello Git World

## git의 주요 개념
- 작업 디렉토리 (Working Directory) : 
- 준비 영역 (Staging Area, Stage/Index) :
- 로컬 저장소 (Local Repository) :
- 원격 저장소 (Remote Repository) :

## 기본 명령어
- git init : 로컬 저장소 초기화 (.git 파일 만듦)
- git status : 로컬 저장소의 상태
  - D : Deleted
  - M : Modify
  - ?? : New
- git add : 작업 디렉토리에서 준비영역으로 올림
- git commit : 준비 영역에서 로컬 저장소(.git)로 올림
- git commit -m "msg" : 커밋 메세지 작성
- git commit -am "msg" : add + 커밋 메세지 작성
- git push : 로컬 저장소에서 원격 저장소(ex-github)로 올림
- git log : 커밋 내역 보여줌
- git reset --hard : 가장 최근에 커밋한 버전으로 롤백
- git rm : 작업 디렉토리와 준비영역에 있는 파일 다 삭제
- git rm --cached : 작업디렉토리에 있는 파일은 건들지 않고, 준비영역에 있는 파일만 삭제

## 제외목록 설정
- [.gitignore 파일](https://git-scm.com/docs/gitignore#_pattern_format)
- [추천 사이트](https://www.gitignore.io/)

## 원격 저장소
- 목록보기 : git remote -v 
- 추가하기 : git remote add [별칭] [주소]
- 삭제하기 : git remote rm [별칭]
- 별칭수정 : git remote rename [기존별칭] [새 별칭]
- 주소수정 : git remote set-url [별칭] [변경할주소]

## 브랜치
- 목록보기 : git branch
- 생성하기 : git branch [새 브랜치명] 또는 git branch [복사할 브랜치명] [새 브랜치명]
- 삭제하기 : git branch -d [브랜치명] 
- 이름변경(이동) : git branch -m [기존 브랜치명] [새 브랜치명]
- 전환하기 : git checkout [브랜치명]
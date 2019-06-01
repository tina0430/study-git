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
- git push : 로컬 저장소에서 원격 저장소(ex-github)로 올림
- git log : 커밋 내역 보여줌
- git reset --hard : 가장 최근에 커밋한 버전으로 롤백
- git rm : 작업 디렉토리와 준비영역에 있는 파일 다 삭제
- git rm --cached : 작업디렉토리에 있는 파일은 건들지 않고, 준비영역에 있는 파일만 삭제
# Hello Git World

## git의 주요 개념
- 작업 디렉토리 (Working Directory) :
- 준비 영역 (Staging Area, Stage/Index) :
- 로컬 저장소 (Local Repository) :
- 원격 저장소 (Remote Repository) :

## 기본 명령어
- git init : 
- git status : 
- git add : 
- git commit : 
- git log : 
- git reset --hard : 
- git rm --cached : 

=======================================================

## 제외목록 설정
- [.gitignore 파일](https://git-scm.com/docs/gitignore#_pattern_format)
- [추천 사이트](https://www.gitignore.io/)

## 원격 저장소
- 목록보기 : git remote -v : 자세히보기
- 추가하기 : git remote add [별칭] [주소] : 추가하기 (별칭은 기본으로 origin)
- 삭제하기 : git remote rm [별칭] : 삭제
- 별칭수정 : git remote rename [기존별칭] [새 별칭] : 이름 바꾸기
- 주소수정 : git remote set-url [별칭] [변경할주소] : 주소바꾸기

## 브랜치
- 목록보기 : git branch
- 생성하기 : git branch [새 브랜치명] 또는 git branch [복사할 브랜치명] [새 브랜치명]
- 삭제하기 : git branch -d [브랜치명] 
- 이름변경(이동) : git branch -m [기존 브랜치명] [새 브랜치명]
- 전환하기 : git checkout [브랜치명]

=======================================================
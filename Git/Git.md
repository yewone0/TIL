## Git 명령어

`git init` : 시작

`git status` : 현재 상태 확인

`git add` : 변경사항이 있는 파일을 staging area에 추가

`git commit -m '이름'` : staging area에 있는 파일들을 저장소에 기록

`git log` : commit history 보기

`git log --oneline` : 한줄로 보기

`git config --global -l` : 글로벌 설정 정보 보기

`git config --global user.name "이름"` : 이름 변경

`git config --global user.email "메일주소"` : 메일주소 변경

---


`git remote add origin url` : 로컬 저장소에 원격 저장소 주소 추가. origin은 추가하는 원격저장소 별칭

`git push -u origin master` : origin이라는 이름의 원격 저장소에 master라는 이름의 브랜치를 업로드

`git pull `: 변경사항만 다운로드

`git remote rm origin` : origin이라는 원격 저장소 삭제

---
저장 순서 : init -> add -> commit

업로드 순서 : local 생성 -> 원격 저장소(github repository) 생성, commit 없는 저장소로 생성 -> remote add -> push
___
<br>

Working Directory : 실제 작업중인 파일들이 위치하는 영역

Staging Area : Working Directory에서 변경된 파일 중, 다음 버전에 포함시킬 파일들을 선택적으로 추가하거나 제외할 수 있는 중간 준비 영역

Repository : 버전(commit) 이력과 파일들이 영구적으로 저장되는 영역
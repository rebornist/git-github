# Git & Github 사용법


git config --global user.name "example"
git config --global user.email "you@example.com"

1. 원하는 폴더에서 git을 초기화
    git init

2. git 초기화를 하면 .git(숨김파일) 파일생성

3. 코딩 중 버전을 생성 및 추가
    git add . 
    git add README.md(원하는 파일만 저장 가능)
    git commit -m "프로잭트 설명 파일"

4. 생성한 커밋 보기
    git log

5. 깃허브 저장소와 연동 
    git remote add origin https://github.com/rebornist/project-name.git

6. 만든 커밋 github 저장소에 올리기
    git push -u origin main

7. 다른 사람이 만든 저장소 받아오기. 협업 설정이 되지 않으면 github에 저장 불가
    git clone https://github.com/ID/Name.git

8. 다른 사람과 협업 중 조치사항
    project -> settings -> Manage access -> Invite a collaborator

9. 다른 사람과의 협업 연결 끊기 및 폴더 제거
    git rm -r --cached removedDir.

10. git GUI 환경 설정
    https://www.sourcetreeapp.com/ sourcetree 다운로드

11. 다른 사람이 PR을 통해서 코드를 업데이트했거나, 아니면 Github를 통해서 commit했을 때(Github를 통해서도 간단한 commit을 할 수 있습니다) 그 내용을 클라이언트로 내려받는 명령어
    git pull origin master
    
12. 깃허브의 유저이름과 비밀번호를 쳐야하는 경우, 매번 비밀번호를 치기 귀찮다면(파일로 저장되는만큼 보안에 취약)
    git config --global credential.helper 'store --file 경로'

13. 브랜치 만들기
    git branch name

14. 브랜치 이동하기
    git checkout name

15. 브랜치 작업 후 main에 병합하기
    git chechout main
    git merge name

16. 충돌해결
    git conflict main

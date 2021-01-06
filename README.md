# Git & Github 사용법

git config --global user.email "you@example.com"

1. 원하는 폴더에서 git을 초기화
    git init

2. git 초기화를 하면 .git(숨김파일) 파일생성

3. 코딩 중 버전을 생성 및 추가
    git add . or git add README.md(원하는 파일만 저장 가능)
    git commit -m "프로잭트 설명 파일"

4. 생성한 커밋 보기 git log

5. 깃허브 저장소와 연동 
    git remote add origin https://github.com/rebornist/project-name.git
    git branch -M main

6. 만든 커밋 github 저장소에 올리기
    git push -u origin main

7. 다른 사람이 만든 저장소 받아오기
    git clone https://github.com/ID/Name.git

8. 다른 사람과 협업 중 조치사항
    project -> settings -> Manage access -> Invite a collaborator

9. 다른 사람과의 협업 연결 끊기
    git rm -r --cached removedDir.
# Git & Github 사용법

1. 원하는 폴더에서 git을 초기화할 때 git init 실행

2. git 초기화를 하면 .git(숨김파일) 파일생성

3. 코딩 중 버전을 생성 및 추가하고 싶을 때 git add 실행 후  git commit 실행
    git add README.md -> 원하는 파일만 저장 가능
    git commit -m "프로잭트 설명 파일"

4. 생성한 커밋 보기 git log

5. 깃허브 저장소와 연동 
    git remote add origin https://github.com/rebornist/project-name.git
    git branch -M main
    git push -u origin main
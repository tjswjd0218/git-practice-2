## Git Command

- `git init`: 현재 디렉토리를 기준으로 Git 저장소 생성
- `git remote add origin <remote repository url>`: 로컬 git 저장소에 원격 저장소를 추가 하는 명령어
- `git add <file name>`:
  다음 변경(commit)을 기록할 때까지 변경분을 모아놓기 위해서 사용
- `git commit`: 변화한 부분을 저장하는 것을 의미,
  언제든지 커밋한 시점으로 되돌아 갈 수 있음
- `git push origin <branch name>`: 원격으로 내용을 업로드하는것
- `git pull origin <branch name>`: 다른 사람이 PR을 통해서 코드를 업데이트했거나, 아니면 Github를 통해서 commit했을 때(Github를 통해서도 간단한 commit을 할 수 있습니다) 그 내용을 클라이언트로 내려받는 명령어
- `git merge <branch name>`: git branch를 다른 branch로 합치는 과정

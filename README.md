# git 명령어
 1. git config 명령어 : 사용자 정보 업데이트 <br>
 2. git init 명령어 : 해당 디렉토리 git 정보 초기화 <br>
 3. git add 명령어 : 해당 파일을  track 시키거나 stage 시키는 명령 <br>
 4. git status : 현재 디렉토리의 내 파일들의 상태를 확인하는 명령 <br>
  - Untracked files : git 관리 상태가 아닌 파일 <br>
  - Changes not staged for commmit : 파일이 수정되었으나 staged 되지 않은 파일 <br>
  - Changed to be committed : staged 되었으나 commit은 되지 않은 파일 <br>
 5. git commit : Stage 된 스냅샷을 Storage에 저장한다.
 6. git clone : 원격 저장소를 local에 복사하는 작업을 수행한다. <br>
 7. git remote / git remote show : 현재 디렉토리의 원격 저장소 정보를 출력한다. <br>
 8. git getch : 현재 스토리지로 원격 스토리지의 최종 스냅샷 상태를 가져온다. <br> 하지만 파일에 merge 하지는 않는다. <br>따라서 현재 디렉토리에 있는 파일의 상태가 바뀌지는 않는다.
 9. git pull : git fetch + git merge와 동일하다.<br> 원격 저장소의 상태를 로컬 저장소로 가져온 후 실제 파일들에 변경된 내용을 merge한다.<br>
 10. git push : 현재 로컬에서 commit한 내용을 리모트 스토리지에 저장한다. <br>
 11. git diff : commit 되어 있는 상태와 현재 로컬 디렉토리에 있는 파일의 상태가 일치하지 않는 경우 해당 차이점 표시 <br> 
 12. git log : 현재까지 commit 된 상태 log 출력
 13. git merge : 현재 로컬 스토리지의 최종 snap shot이 로컬 디렉토리 파일을 merge하는 작업 수행 <br>

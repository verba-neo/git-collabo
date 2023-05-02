# Git 으로 협업하기
## Github 공동작업자 설정
1. `Repositories`에서 `New` 클릭
2. `Repository name`을 설정한 후, `ADD a README file` 및 `Add.gitignore` 선택
3. `Create repository` 클릭하면 문서가 생성된 것을 확인할 수 있다.
4. 새롭게 생성된 `repo`에 들어가 `Settings` > `Collaborators` > 함께 작업할 사람의 아이디 작성

## Github 문서 공유
`$ git pull origin master` : 공동작업자가 새롭게 작성한 내용 github으로부터 다운

`$ git add . ; git commit -m '<branch-name>` : 새롭게 작성된 내용을 추가하여 커밋

`$ git push origin master` : 내가 새롭게 작성한 내용 github에 업로드
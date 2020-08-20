# Git Command

#### git init

깃 초기 설정해주는 명령어이고 .git/ 생성시킴

#### git status

깃 상태 출력

#### git add 파일명

스냅샷을 찍기 위해 무대에 올리는 작업.  working directory에 있는 것을 staging area로 추가

#### git add .

내가 가지고 있는 모든 폴더와 파일을 add

#### git commit -m "message"

커밋을 통해 스냅샷 찍음. local repo(.git/)으로 commit함. message에는 변경사항 적어주는게 관례

#### git config --global user.email "email" 

이메일 등록

#### git config --global user.name "name"

이름 등록 . 정보가 .git config 파일에 저장됨

#### git diff 

변경사항 확인

#### git log

commit사항 변경이력 확인

#### git remote add origin https://github.com/Lee-Geon-Yeong/git.git

깃아 리모트(어디에 올릴지에 대한 원격 저장소) 저장소를 추가해줘 별명은 origin이고 원래 주소는 https://github.com/Lee-Geon-Yeong/git.git야

#### git remote -v

리모트 주소 확인

#### git remote remove origin

리모트 주소 잘못 적었을 경우 삭제하고 다시 추가해줘야 함

#### git push origin master

github의 remote repo에 push하여 저장


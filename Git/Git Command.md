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

#### git push origin master or git push origin +master

github의 remote repo에 push하여 저장

#### gitignore.io -> 개발할 때 불필요한 파일들은 깃허브에 업로드 하지 않음 

<<<<<<< HEAD
#### git pull origin master

github의 오리진 마스터를 불러옴 

#### github에서 다른 사람에게 협업 콜라보 요청 보내기

settings-> manage access-> invite a collaborator

#### git 과거버전으로 가기

git checkout 과거버전해쉬값

#### git 과거버전에서 다시 현재버전으로 가기

git checkout master

#### git 브랜치 목록 보여주기

git branch

#### git 브랜치 생성하기, 삭제하기

git branch -c <branch name>

git branch -d <branch name>

#### git 브랜치 이동하기

git switch <branch name>

#### git 마스터에 브랜치에서 작업한 거 병합하기

git switch master (먼저 master로 가서)

git merge <합치고자하는 branch name>

#### 상대방 branch 가져오기

git pull origin <상대방 branch name>

git fetch origin <상대방 branch name : branch name>feature_junehan:feature_junehan(Tab 이용)

#### 브랜치 머지

pull requests -> compare&pull request -> create pull request -> merge

#### 깃 협업 프로젝트 하기

1. 메인테이너 정하기
2.  프로젝트 생성
3. git init
4. gitignore
5. git add
6. git commit
7. git push



1. 각자 프로젝트 하기
=======
#### 파이참에서 깃배쉬 설정하는 법 
ctrl+alt+s 설정 진입 -> tools ->terminal -> C:\Program Files\Git\bin\bash.exe

#### 다른사람꺼 클론하는 법 
code->다른사람꺼 주소 복사
git clone https://github.com/StartBootstrap/startbootstrap-resume.git
다른사람꺼의 리모트 주소를 삭제
git remote remove origin
내 리모트 주소로 연결
git remote add origin https://github.com/Lee-Geon-Yeong/Lee-Geon-Yeong.github.io.git
깃 푸쉬
git push origin master
>>>>>>> 63bcfcb97a4c6d0759fa9e006a0c29a8620959a8

git config --global core.autocrlf true

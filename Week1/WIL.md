# 1주차 WIL

* ### Git을 왜 쓰는가?
   ###### 코드의 수정을 관리해야한다.
   ###### 잔뜩 쌓인 파일들을 관리해야한다.
   ###### 개발은 혼자 하는 것이 아니다.
   ###### 버전 관리가 필요하다.
   #### 따라서 어떤파일이 수정되었는지, 누가 수정했는지, 언제 수정되었는지, 어떻게 수정되었는지 알기 위해서 Git을 사용한다.
* ###  Git은 무엇인가?
    ###### Git은 버전 관리 및 협업을 위해 사용하는 오픈소스 소프트웨어이다.
* ### Git의 영역   
    ###### Working Directory
    ###### Staging Area
    ###### Repository
* ### Git으로 파일 관리하는 법
   ###### 1. 디렉토리에 Git 저장소를 만들기 (git init)
   ###### 2. Git으로 관리할 대상 등록하기 (git add)
   ###### 3. 파일 수정 후 로컬 저장소로 옮기기 (git commit)
* ### GitHub는 왜 쓰는가?
   ###### 하고있는 작업을 온라인으로 공유하여 저장하고 타인과 협업하기 위해서!
* ### GitHub의 기능
    ###### 이슈 트래킹 (버그 보고, 기능 개선 건의 등 프로젝트에 관련된 주제를 등록할 수 있는 게시판)
    ###### 코드 리뷰
    ###### GitHub Actions로 CI/CD
    ###### GitHub Projects로 프로젝트 업무 관리
* ### 실습하기!
   ###### 1. 비주얼 스튜디오와 깃 설치하기
   ###### 2. 깃 최초설정하기 (git config --global user.name"깃허브 이름", git config --global user.email"깃허브 이메일") 
   ###### 3. 디렉토리 만들고 .git 폴더 만들기
   ###### 4. 디렉토리를 깃 저장소로 만들기 (git init)
   ###### 5. 깃으로 관리할 파일 만들기
   ###### 6. 깃으로 관리할 대상 등록하기 (git add .:모든 파일 한번에, git add 파일명: 하나씩 등록, git rm --cached 파일명: unstage로 되돌리기)
   ###### 7. 파일 수정 후 로컬 저장소로 옮기기 (git commit -m "메시지") (무엇을 수정하였는지 한눈에 알아보기 위해 Commit Message는 "type : subject" 형식을 이용한다. type- feat: 새로운 기능을 추가한 경우, refactor: 기존 코드를 개선한 경우, fix: 버그를 수정한 경우, chore: 코드 외의 설정을 바꾼 경우, docs: 문서화, test: 테스트 코드)
* ### 소감
    ###### 노트북 가져가는 것을 깜빡해서 오프라인에서는 듣기만 하고 집에서 실습을 해보았다. 실습하는 것이 처음이라 기대되기도 하고, 긴장되기도 하였다. 술술 진행되는 것 같았는데 내가 VS코드에 쓴 내용이 깃허브에 올라가지 않아서 막히게 되었다. 영상을 그대로 따라했는데 오류가 발생해서 구글링도 하고, 새로운 repo도 만들면서 5시간동안 사투를 벌였으나 해결되지 않았다. 마침내 해결을 하였는데 VS코드에 내용을 입력하고 저장하지 않은 채 git push를 했던 것이 문제였다. 허무했지만 오류를 통해 결과적으로 여러번의 복습을 했다는 것을 위안으로 삼고 다음 스터디를 준비해야겠다. 

https://github.com/HS-1024/HS-1024

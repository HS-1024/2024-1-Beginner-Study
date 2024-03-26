# 2주차 WIL

* ### GitHub의 Fork
    ##### 다른 사용자의 Repository를 자신의 계정으로 복사하여 독립적으로 수정하고 관리하는 기능
    ##### clone을 하면 다른 사용자의 프로젝트를 사용하거나 보기만 할 수 있지만, fork를 하면 프로젝트에 대한 수정, 관리 권한이 생김
* ### GitHub의 Star
    ##### 관심 있는 Repository나 프로젝트에 star를 달아 "북마크"와 같이 관리하는 기능
    ##### 필요한 기능을 구현하기 위해 GitHub 프로젝트들을 검색하고 다운받을 때 star 개수를 통해 프로젝트의 신뢰도를 가늠하기도 함
* ### Issue
    ##### Repository에서 작업 계획, 토론 및 추적을 위해 활용
    ##### 프로젝트 기획, 새롭게 추가될 기능, 버그와 수정사항 모든 것을 issue라고 할 수 있음
* ### Branch
    ##### 기존 브랜치에서 분기되어 생성되는 별도의 작업 공간
    ##### fork와 달리 같은 Repository에 생성됨
    ##### 필요에 의해 만들어지는 각각의 브랜치는 다른 브랜치의 영향을 받지 않기 때문에, 여러 작업을 동시에 진행할 수 있음
    ##### Branch Naming Convention: "type/issue번호-간략한설명"
* ### Pull Request
    ##### 분기된 Branch를 다시 병합하기 위한 절차
    ##### 새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결
    ##### Merge에 앞서 코드 리뷰
* ### Merge
    ##### 1. Merge Commit: 두 브랜치를 공통 부모로 하는 새로운 커밋을 만듦, 어떤 브랜치에서 어떻게 만들어져서 머지가 되었는지 상세하게 파악할 수 있음
    ##### 2. Squash and Merge: 개발용 브랜치의 내용들을 하나로 합쳐 중앙 브랜치에 하나의 커밋으로 저장, 변경사항들이 어떻게 변했는가 보다 머지가 되었다에 집중한 전략, Merge Commit에 비해 커밋에 남아있는 정보량이 비교적 적기 때문에 언제 어떤 코드를 바꿨는지에 대한 정보를 잃을 수 있음
    ##### 3. Rebase and Merge: 베이스의 위치를 변경해서 다른 브랜치에서 커밋한 내역을 최신으로 보고 그대로 끌어오는 식으로 합치는 것, 중복 로그를 남기지 않고, 머지로그를 줄여 히스토리를 깔끔하게 정리할 수 있다. 히스토리를 지우는 것이므로 무수한 충돌을 경험할 수 있음
* ### 실습
    ##### 1. Issue 만들기: title과 description 작성
    ##### 2. Branch 만들기: 현재 브랜치 확인 (git branch), 모든 브랜치 확인 (git branch -a), 브랜치 생성하기 (git branch "브랜치 이름"), 브랜치 삭제하기 (git branch -D "브랜치 이름")
    ##### 3. Branch - checkout: 브랜치 이동하기 (git checkout "브랜치 이름"), 브랜치 생성 후 이동하기 (git checkout -b "브랜치 이름")
    ##### 4. Readme.md 만들기 
    ##### 5. Commit하기: git commit -m "메시지"
    ##### 6. Push하기: git push origin <브랜치 이름>
    ##### 7. Pull Request 만들기
    ##### 8. Merge 하기: Squash and merge 이용

https://github.com/HS-1024/2024-1-Beginner-Study/pull/2


# TeamProject

## git repository 생성하기 : 팀장이 하는일
```
git init
git commit -m "first commit"
git remote add origin https://github.com/hykim6856/TeamProject.git
git push -u origin master
```

## Collaborators 설정하기
* 원격 Repository 의 `Settings/Collaborators` 메뉴에서 (git)회원 id 검색하여 추가하기
* 추가 된 회원은 본인 email에서 확인하기

## 원격 Repository clone 하기
* 각 회원들은 팀장의 원격 Repository 를 workspace 폴더에서 `clone` 하기
* clone 한 프로젝트 폴더에서 다음작업 계속하기

## 주의사항
* 절대 같은 파일을 두명 이상이 편집하지 않는다.
* `.gitignore` 파일 관리를 잘 해야한다. 만약 ide 도구중 자동으로 변경되는 파일들이 repository에 섞여서 push 될 경우 여러가지 문제를 일으킨다.
* 반드시 `branch`를 구분해야한다.

## branch 구분하기!!
* `git checkout -b 'branch명'`
* `git branch (branch명)`, `git checkout branch`
* checkout 을 실행하면 새로운 branch로 작업환경이 전환된다.

* 프로젝트 진행하기...

## 작업한 내용 원격 repository 에 commit(push)하기
* `git add .`
* `git commit -m 커맨드`
* `git push origin hykim6856` : 작업하고 있는 branch 명 반드시 써주기

## pull request 하기
* 원격 repository 에서 자신이 올린 branch 를 선택 
* `compare & pull request` 요청하기
* 이때 가급적이면 pull request 를 요청한 이유를 상세하게 작성하기
* `pull request` 버튼 클릭하여 요청완료

## 팀장이 `merge` 하기
* 프로젝트의 상단 메뉴에서 `pull request` 배지 확인
* 해당 pull request를 열고 내용 확인하기
* 확인 완료되고 정상 pull request 임이 확인되면, `merge` 하기

## 팀원들이 merge된 프로젝트 pull하기
* 로컬 repository에서 다시 master branch 로 이동 : `git checkout master`
* 원격에서 pull 해오기 : `git pull origin master`

## 팀원들이 자신의 작업 branch 와 master 동기화 하기
* 작업 branch 로 이동 : `git checkout callor`
* master 와 동기화 : `git merge master`

* `git commit -m"커맨트"`
* `git push origin hykim6856` 작업자명 꼭 입력하기

* 노션주소 https://www.notion.so/c9bb25c2ee934a6c94ae3d8c4552a962?v=1a2b4ea5de4c4efd928eb8092b5de626

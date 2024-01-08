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
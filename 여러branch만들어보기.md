# Branch

- 프로젝트를 하나 이상의 모습으로 관리해야 할 때
- 여러 작업들이 각각 독립되어 진행될 때

## 브랜치 생성/이동/삭제

- `브랜치 생성`
```
$ git branch (branch이름)
```

- `브랜치 목록 확인`
```
$ git branch
```

- `브랜치 이동`
    - `checkout 명령어는 Git2.23버전부터 switch,restore로 분리`
```
git switch (브랜치이름)
```

- `브랜치 이름 바꾸기`
```
$ git branch -m (기존 브랜치 이름) (바꿀 브랜치 이름)
```

- `브랜치 삭제하기`
```
$ git branch - d (삭제할 브랜치 이름)
```

- `브랜치 강제 삭제하기`
    - `지워질 브랜치에만 있는 내용의 커밋이 있을 경우`
```
$ git branch -D (강제 삭제할 브랜치 이름)
```

- `브랜치 내역보기`
    - `위치한 브랜치에서의 내역만 볼 수 있음`
```
$ git log
```
- `여러 브랜치 내역 보기` 
```
$ git log --all --decorate --oneline --graph
```

# push 와 pull

## 원격으로 커밋 밀어올리기(push)

```
$ git push origin main
```

- `이미 git push -u origin main으로 대상 원격 브랜치가 지정되었을 때`
```
$ git push
```

## 원격의 커밋 당겨오기(pull)

```
$ git pull origin main
```

## pull 할 것이 있을 때 push를 하면?

- 원격에 먼저 적용된 새 버전이 있으므로 적용불가
- pull 해서 원격의 버전을 먼저 받아온 다음 push 가능

- push할 것이 있을 시 pull 하는 두가지 방법

- `git pull --no-rebase` merge방식

- `git pull --rebase` rebase방식
    - pull상의 rebase는 다름(협업시 사용OK)

## 로컬의 내역 강제 push해보기

```
$ git push --force
```

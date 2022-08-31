# branch 합치기 실습

- `merge`로 합치기
    - `main` 브랜치로 이동후 `merge`

```
$ git merge (합칠 브랜치)
```

- `rebase`로 합치기
    - `합칠 브랜치`로 이동후 `rebase`
    - `rebase` 하고 `소스트리`에서 보면 main 브랜치가 `합칠 브랜치`보다 뒤쳐져 있는 상황
    - `main` 브랜치로 이동 후 `merge`

```
$ git rebase main
```

```
$ git merge (합칠 브랜치)
```

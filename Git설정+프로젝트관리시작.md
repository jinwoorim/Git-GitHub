# Git 최초 설정

- Git전역으로 사용자 이름과 이메일 주소를 설정(GitHub 계정과는 별개)

```shell
git config --global user.name "(본인이름)"
```
```shell
git config --global user.email "(본엔 이메일)"
```

- 확인

```shell
git config --global user.name
```
```shell
git config --global user.email
```

- 기본 브랜치명 변경(디폴트는 master)(master에서 main으로 변경)

```shell
git config --global init.defaultBranch main
```

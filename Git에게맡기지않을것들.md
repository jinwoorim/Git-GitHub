# Git의 관리에서 특정파일/폴더를 배제해야 할 경우

- 포함할 필요가 없을때
    - 자동으로 생성 또는 다운로드되는 파일들(빌드결과물,라이브러리)
- 포함하지 말아야 할 때
    - 보안상 민감한 정보를 담은 파일

- .gitignore 파일을 사용해서 배제할 요소들을 지정할 수 있다

- .gitignore 파일에 숨기고 싶은 파일을 집어넣는다

# .gitignore 형식 

- [https://git-scm.com/docs/gitignore](https://git-scm.com/docs/gitignore) 참조

- .gitignore 범위 설정

```shell

# 모든 file.c
file.c

# 최상위 폴더의 file.c
/file.c

# 모든 .c 확장자 파일
*.c

# .c확장자지만 무시하지 않을 파일
!not_ignore_this.c

# logs란 이름의 파일 또는 폴더와 그 내용들
logs

# logs란 이름의 폴더와 그 내용들
logs/debug.log
logs/*.c

# logs 폴더 바로 안, 또는 그 안의 폴더 안의 debug.log
logs/**/debug.log
```

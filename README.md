# go-standard-structure
> [Standard Go Project Layout](https://github.com/golang-standards/project-layout) 을 참고하여 최초 go project 구성시 구조를 생성한다.

### gitlab mirror 허용 설정
- gitlab project > Settings > Repository > Protected branches 이동
- main 브랜치의 "Allowed to force push"를 허용한다.
### mirror 실행
```bash
git clone --mirror git@gitlab.scglab.com:jwpark7/go-standard-layout.git
cd go-standard-layout.git
git remote set-url --push origin ${신규_리파지토리_주소}
git push --mirror
```
## GIT

# Basic Workflow

```sh
$ git init
$ git status # 빨간색
$ git add .
$ git status # 초록색 확인. 초록색만 커밋됨
$ git commit -m'짧고 간결한 현재형'

#github, bitbucket, gitlab etc.. remote repo를 생성
$ git remote add origin <REMOTE REPO URL.git>
$ git push (-u origin master) #맨 처음에만

#다른 컴퓨터라면,
$ gt clone <REMOTE REPO URL.git> # download ZIP = .git 없움 ㅠ

#작업작업
$ git add . && git commit -m 'MSG' && git push # 앤드로 묶이면 에러나면 멈춤. 뒤에 진행 안 함.
$ git add . ; git commit -m 'MSG' ; git push # 에러나도 계속 할려그럼. 꼬일 수 있음.
$ git pull
```


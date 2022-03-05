## git 환경 설정 
 'git config' tool 이용
 
  config file in the Git directory (.git/config)

### 로컬에서 만든 브랜치라면
 ```
  $ git init
  $ git remote add origin [레포지토리 url]
  $ git remote -v
 ```

### identity 설정
  가장 먼저 identity 설정해 줘야 함.(username, email)

 ```
  $ git config --global user.name "John Doe"
  $ git config --global user.email johndoe@example.com
 ```

 ### 기본 브랜치 이름 변경
  ```
  $ git config --global init.defaultBranch main
  ``` 

### config 설정 확인
 ```
  $ git config --list
 ```

 
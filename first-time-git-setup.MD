## git 환경 설정 
 'git config' tool 이용
 
  config file in the Git directory (.git/config)

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

 
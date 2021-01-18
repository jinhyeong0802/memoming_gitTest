# memoming_gitTest

git upload test

### Git 초기화
$ git init 

### Local Project를 Add를 통해 Staging to index 
$ git add . 

### Staging을 실제 Local Repository로 저장 
$ git commit -m "First Commit to existed local project" 

### Remote Repository로 Push를 위 한 URL설정 및 확인 
$ git remote add origin “ repository URL “   
$ git remote -v 

### Local to Remote Repository Push 
$ git push orign master

### pull
$ git pull origin master

### push
$ git push origin master   
출처: https://secuinfo.tistory.com/entry/Local-Project-GitHub [Song's Lab]


# Error

### fatal: refusing to merge unrelated histories
$git pull origin 브런치명 --allow-unrelated-histories   
* error: failed to push some refs to 'https://github.com/sy2399/ML_Basic.git'   
git push -u origin +master

### Git ignore
$ touch .gitignore     #git ignore 파일 생성   
$ git rm -r — cached  # git 에 이미 올라간 파일을 ignore 하려는 경우, git 에 올라간거 지우기!
$ git rm -rf —cached 


https://gmlwjd9405.github.io/2018/05/17/git-delete-incorrect-files.html

### Git 폴더 이름 변경 or 삭제시
git add -u

# Stash

커밋은 하지않고 다른 공간에 따로 치워두기   
ex) 작업을 하다가 갑자기 급한 작업이 들어왔을 때

### 1. 따로 치워두기  
```git stash``` 

### 2. 원하는 것만 stash 해보기 
``` git stash -p```

### 3. 메시지와 함께 스태시
```git stash -m 'Add Stash3'```

### 4. stash 목록보기
```git stash list```

### 5. 적용하기
```git stash apply``` : 치워둔 마지막 항목 적용
```git stash drop``` : 치워둔 마지막 항목 삭제
```git stash pop``` : 치워둔 마지막 항목 적용 및 삭제


## Stash 사용법 정리

|명령어|설명|
|--|--|
|git stash|현 작업들 치워두기|
|git stash apply|	치워둔 마지막 항목(번호 없을 시) 적용|	
|git stash drop|치워둔 마지막 항목(번호 없을 시) 삭제	|
|git stash pop|치워둔 마지막 항목(번호 없을 시) 적용 및 삭제	apply + drop|
|💡 git stash branch (브랜치명)	|새 브랜치를 생성하여 pop|
|git stash clear	|치워둔 모든 항목들 비우기	|

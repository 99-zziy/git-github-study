## branch

### 1. branch 생성
```git branch 브랜치명```

### 2. branch 이동
```git switch 브랜치명```

### 3. branch 생성 후 이동
```git switch -c 브랜치명```

### 4. branch 삭제
```git branch -d 삭제할 브랜치명```

### 5. branch 명 수정
```git branch -m 기존 브랜치명 새 브랜치명```

## branch 합치기

#### merge : 두 브랜치를 한 커밋에 이어붙입니다.

브랜치 사용내역을 남길 필요가 있을 때 적합한 방식입니다.  

#### rebase : 브랜치를 다른 브랜치에 이어붙입니다.

한 줄로 깔끔히 정리된 내역을 유지하기 원할 때 적합합니다.  
이미 팀원과 공유된 커밋들에 대해서는 사용하지 않는 것이 좋습니다.

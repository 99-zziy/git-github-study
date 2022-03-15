# git rebase -i (대상 바로 이전 커밋)

과거 커밋 내역을 다양한 방법으로 수정 가능

|명령어	|설명|
|--|--|
|p| pick	커밋 그대로 두기|
|r| reword	커밋 메시지 변경|
|e| edit	수정을 위해 정지|
|d| drop	커밋 삭제|
|s| squash	이전 커밋에 합치기|

<br/>  
    
**e 명령어로 수정 시작**  
git reset HEAD~  
변화들을 따로 스테이지 및 커밋  
git rebase --continue

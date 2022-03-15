# git의 장점

## 1. snapshot 
<img width="559" alt="스크린샷 2022-03-15 오후 9 04 33" src="https://user-images.githubusercontent.com/62633444/158374073-2b430756-bb32-4061-82d6-2b018c345b79.png">

델타 방식 
- SVN은 개별 파일별로 변화를 감지해서 스냅샷을 저장한다. 

스냅샷 방식
- Git은 저장소의 파일 시스템 전체를 스냅샷으로 취급한다. 

참고(https://tech.10000lab.xyz/git/how-git-is-different.html)

## 2. 분산 버전 관리
<img width="1086" alt="스크린샷 2022-03-15 오후 9 17 01" src="https://user-images.githubusercontent.com/62633444/158375941-94fa5fe5-5804-4102-8769-4f1b284d5cb9.png">


기존의 SVN은 소스 관리를 위한 중앙 서버를 두었다.
하지만 Git은 저장소에 push하고 pull를 하면서 다른사람들과 저장소를 공유하게 되는 방식이다. 

참고(https://antilog.tistory.com/61)

# git의 3가지 공간


<img width="1075" alt="스크린샷 2022-03-15 오후 9 33 18" src="https://user-images.githubusercontent.com/62633444/158378458-60083772-ed4f-4c30-8eeb-f780d92b13b3.png">

- **Working directory**  
untracked: Add된 적 없는 파일, ignore 된 파일  
tracked: Add된 적 있고 변경내역이 있는 파일

- **Staging area**  
커밋을 위한 준비 단계

- **Repository**  
커밋된 상태

**🤔 파일을 staging area에서 working directory로 이동하려면?**
```
git restore --staged (파일명)
```

### reset의 세 가지 옵션
--soft: repository에서 staging area로 이동  
--mixed (default): repository에서 working directory로 이동  
--hard: 수정사항 완전히 삭제


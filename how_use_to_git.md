# git 사용법 정리

>원격저장소  
1. 원격저장소 등록  
git remote add document  
//document라는 원격 저장소 등록

2. 원격저장소 추가  
git remote add test  
//test라는 원격 저장소 추가  

3. 원격저장소 내려받기  
git clone [원격저장소 주소]  
//깃허브에 있는 원격 저장소를 클론을 통해 내려받음


>브랜치  
1. 브랜치 생성  
git branch [브랜치 이름]  
// 새로운 브랜치를 생성함

2. 브랜치 변경  
git checkout [브랜치 이름]  
//변경하고자 하는 브랜치로 변경

3. 브랜치 삭제  
git branch -d [브랜치 이름]  
//브랜치를 삭제함
  
>저장소에 데이터 올리기  
* add (git add)  
Working Directory에서 작업하던것을 Staging Area로 올림
* commit (git -m "~~")  
Staging Area 올라온 파일들을 Local Repository에 반영함

* push (git push)  
Local Repository에 반영된 파일들을 원격저장소에 보냄.

* pull (git pull)  
원격저장소(Remote Repository)에 있는 파일들을 Local Repository로 내려받음.  

>실습결과  

![실습1](https://user-images.githubusercontent.com/116232686/198332708-2e399f32-6657-41c1-a7f6-c1e518f12ac2.jpg)  

![실습2](https://user-images.githubusercontent.com/116232686/198332717-c1ce2070-ca1c-4f1f-8f6b-fb66a7c61e56.jpg)  

![실습3](https://user-images.githubusercontent.com/116232686/198332723-96a60589-8816-4247-a431-c77508c01803.jpg)ㄴ

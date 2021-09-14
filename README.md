# Prj_myNas
개인용 헤놀로지 자작 NAS 구축

## :computer: Used
- VMware Workstation
- iptime
- DS3615xs

## :memo: NAS 구축한 이유
![image](https://user-images.githubusercontent.com/40004210/133265585-64a756af-34f6-4af7-9a3f-85895f26441c.png)  
전산실에서 시놀로지를 처음 발견하고 문득 내가 NAS를 만들 수 없을까 의문이 들게됨. 헤놀로지란 가상머신으로 동작하는 스토리지의 존재를 발견! 사실 클라우드 서비스를 이용해도 됐지만 좀 더 의미있는 작업이 되지 않을까해서 시작하게됨.

## :mag: 준비 과정
![image](https://user-images.githubusercontent.com/40004210/133265875-ea3eb8b0-1437-4ab5-afeb-d55a4db6a0e0.png)  
우선 미래를 생각하여 용량이 크고 안정적인 HDD가 필요했음. 따라서 진동에 안정적이고 A/S가 보장되는 WD HDD RED 3TB를 구매함. 가격은 14만원 정도 했던걸로 기억함.

그러면 앞으로 내 데스크톱에는 24시간 가상머신이 돌아가야 하기 때문에 부품 교체가 필요하다는 것을 느낌. 따라서 CPU를 저전력으로 변경하고 RAM을 저전력 32GB로 업그레이드함. 이때 나의 메인보드가 DDR3밖에 지원한다는 충격을 맛봄.

이후, 부품들이 도착하기 전까지 관련 정보를 배우기 위해 여러 전문가에게 자문을 구함.

## :clipboard: 결과
![image](https://user-images.githubusercontent.com/40004210/133266732-cffc2dde-f239-4852-888f-10568c6cd850.png)   
![image](https://user-images.githubusercontent.com/40004210/133267605-080f6cde-c5c1-415b-972c-b09e9ab5de30.png)   
![image](https://user-images.githubusercontent.com/40004210/133267182-85923a0a-3d45-450c-823f-d7522323cd3f.png)   

결론부터 말하면 구축 성공!
일주일 동안 안정적인 스토리지를 구현하기 위해서 정말 이것만 알아본 것 같음...
만약 내가 밖에서 중요한 업무를 진행 중인데 컴퓨터가 꺼진다면? 파일이 날아간다면? 전송이 중지된다면? 속상할 것 같아서

어쨌거나 진행하면서 겪었던 문제점을 하나 씩 살펴보자면

**공유기 이슈**

**맥북 포트포워딩**

**윈도우 강제 업데이트로 데스크톱 종료**

**스토리지 백업**

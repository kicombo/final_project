# final_project


조별로 온라인에서 텍스트로 즐길 수 있는 머드게임을 제작한다.  
뼈대코드는 https://codesandbox.io/s/sleepy-blackburn-ixxn0?file=/src/readme.md:606-625 를 참고한다.  

## 기본 구성

수업시간에 배운 express, mongoose르 활용하여 개발한다. 
상태의 변화는 별도의 데이터베이스에 실시간으로 저장되어야 한다.  
아이템, 맵 등의 정보는 json형태로 서버에서 따로 보관하고 있어야 한다.  


## 기본스펙

뼈대 코드를 기본으로 하여 다음이 구현되어 있어야 한다.  
모든 행동들은 서버에서 이루어지나, 클라이언트에서 별도로 확인이 가능하여야 한다.(html 결과창에 결과가 프린트되면된다)
- [ ] 온라인에서 플레이가 가능하다( codesandbox 등을 활용)  
- [ ] 로그인, 회원가입  
- [ ] 10 * 10 이상의 맵  
- [ ] 캐릭터의 이동  
- [ ] 이동 시 필드별로 아무일도 일어나지 않음, 전투, 아이템 획득의 일이 일어남.
- [ ] 5종 이상의 몬스터  
- [ ] 5종 이상의 아이템  
- [X] 전투 시스템( str, def, hp 개념을 활용)  
- [ ] 사망 시스템(전투 시 hp가 0이될 경우 캐릭터, 가 사망. 0,0 위치로 이동)  
- [ ] 레벨 시스템( 일정 이상 경험치 획득 시 캐릭터 레벨업.)

## 추가스펙

추가 스펙은 조별로 구현가능한 부분을 구현하면 된다.


- [ ] 체력회복하는 이벤트가 추가된다.
- [X] 필드에서 일어나는 이벤트 중 랜덤이벤트가 존재한다.  
- [ ] 아이템을 소유할 경우, 캐릭터의 능력치가 향상된다. 능력치가 클라이언트에서 확인이 가능하다.  
- [ ] 시작 능력치가 랜덤하게 주어지며, 5번에 한하여 재시도가 가능하다. 
- [ ] 사망시 랜덤하게 아이템을 잃어버린다.  
- [ ] 유저의 인벤토리가 클라이언트 상에서 확인이 가능하다. 
- [X] 전투 중, 10턴 안에 전투가 끝나지 않거나, 체력이 20% 이하로 감소할 경우 도망가는 선택지가 추가로 주어진다.


## 제출

조별로 github public repositiry 주소를 발표전에 github issue에 적어 제출한다.(조 번호 , 조원 리스트, codesandbox url 포함)  


## 발표 

12.22 18시에 조별로 진행물과, 진행과정에 대한 발표를 진행한다.   
발표 평가는 강사 평가(20) + 조별 평가(80)으로, 발표전에 미리 제공하는 체점표에 의거하여 각 개인이 다른 조를 평가한다.
체점표는 주제, 문제해결, 제품의 마감 세 가지를 기본으로 하여 제공된다.  
발표의 심미성은 크게 평가대상이 아님.


## 평가

발표(40) + 코드평가(60) 으로 이루어진다.  
코드평가는 github 기여에 따른 개인 평가가 포함된다.  

Cloud 개요

# 목차
1) Cloud 특징
2) Cloud Type
3) Cloud 주요 용어
4) Azure Global Infra


## 1) Cloud 특징

   - 소비 기반 모델
   - 기존의 베어메탈은 자본지출, 클라우드는 운영지출의 개념이다.
   

## 2) Cloud Type

   - Public Cloud : 
      * 클라우드 서비스 또는 호스팅 공급자가 소유
      * 여러 조직과 사용자에게 리소스와 서비스를 제공
      * 초기 투자비용 없음 / 민첩성 / 소비기반모델  
   - Private Cloud : 
      * 클라우드 리소스를 사용하는 조직이 소유 및 운영
      * 조직은 그들의 데이터 센터에 클라우드 환경을 구성
      * 조직에게 본인들이 제공하는 서비스를 운영할 책임이 있음
      * 제어력과 보안이 중요시될 경우 사용      
   - Hybrid Cloud : 
      * 업체는 하이브리드 클라우드 설정을 통해 애플리케이션을 사설 클라우드에서 실행할지, 공유 클라우드에서 실행할지 결정할 수 있다.
      * 다른 업체의 클라우드를 혼합하여 사용할 수 있고, 퍼블릭/프라이빗을 섞을 수 있는 유연한 접근 방식
      
    - 공급자/사용자 사이의 관리영역에 따라 아래와 같이 나눌 수 있다. 
      * On-premises : (Private Cloud) 모든 책임은 사용자
      * IaaS : 고객이 VM부터 책임
      * PaaS : 고객이 Application부터 책임
      * SaaS : 고객이 제공되는 Service의 Data 및 Access에 대한 책임


## 3) Cloud 주요 용어

   - Fault Tolerance : 내결함성
   - High Availability : 고가용성
   - Disaster Recover : 재해복구
   - Scalability : 확장성
   - Elasticity : 탄력성


## 4) Azure Global Infra
    
   - Geography [지리] : 중앙아시아 / 아시아 / 유럽/ 미주 4개로 나눔
   - Region [지역] : 사용자는 지역까지만 선택할 수 있다. [한국(중부), 한국(남부)...]
      * 지역은 불바다가 될 수 있으니, 각각의 Region은 Paired Region을 가진다.
        [한국 중부 Region <-> 한국 남부 Region]
      * Paired Region은 상호간의 DR을 담당한다.
   - Availability Zones [가용성 영역] : 
      * Azure Region 내에서의 물리적 분리
      * 하나 혹은 그 이상의 데이터 센터로 구성되며, 독립된 전원 및 네트워크를 보유
      * 독립적으로 동작하며, 하나의 가용성 영역에 장애 시, 다른 영역에서 연속적으로 서비스
    - Availability Set [가용성 집합] : 
      * WEB-WAS-DB 티어의 묶음 2개가 2개의 VM에 중복되면 1개의 VM이 내려가도 문제가 없다.
      * WEB-WAS-DB 티어의 묶음 2개가 2개의 VM에 중복되고, 각 VM이 서로다른 가용성 영역에 있으면 더 안전하다.
      
   
      

# Azure 개요
[Test Exam : https://www.examtopics.com/exams/microsoft/az-900/]

# 목차
1) Azure Global Infra
2) Azure 리소스에 대한 논리적인 구분
3) Azure Plan 비교


## 1) Azure Global Infra
    
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


## 2) Azure 리소스에 대한 논리적인 구분
    
   * Azure Subscription [구독] : 
      * Cost, Access Control, Technical Limit의 기본 단위
      * Azure Account는 한개 혹은 여러개의 구독을 가질 수 있다.
      * 구독의 종류 : 
         -> 무료 : Azure Free Account [30일 동안 200불 한도의 무료 계정]
         -> 종량제 : Pay as you go
         -> 학생 : 난 아님
      
   * 비용계획 및 관리 : 
      * Azure의 고객유형 : 
         -> 기업고객 : 연간 협상된 금액을 지출하는 계약을 기반
         -> 일반고객 [웹 구매] : 
         -> 클라우드 솔루션 공급자 (CSP) : Microsoft 파트너
         
   * 비용에 영향을 미치는 요인 : 
      * Resource Type : 배포하는 리소스의 유형에 따라 가격책정 방식이 다름
      * Customer Type : Enterprise, Web Direct, Partner 고객에 따라 가격이 다름
      * Location : 리소스를 제공하는 Region에 따라 비용이 다름
      
   * 청구영역 : 
      * Azure로 들어오는 인바운드 데이터는 무료 [대역폭]
      * Azure 아웃바운드 데이터 전송의 경우 과금
      * Region의 경우 지리와는 달리 청구를 목적으로 분할된 것으로 Region 내부의 데이터 전송과 Region 사이의 데이터 전송의 가격 다름
      * 가격 계산기 : Azure 리소스 구성에 따른 비용을 예상하는데 사용
      * 총소유비용 [TCO] 계산기 : 온프레미스 환경을 입력하여 Azure 마이그에 따른 총 연간 비용을 견적으로 볼 수 있음
        [TCO : Total Cost of Ownership]

      

## 3) Azure Plan 비교
    
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
         
      
      
      
      

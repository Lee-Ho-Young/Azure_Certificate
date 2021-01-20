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
         
      
      
      
      

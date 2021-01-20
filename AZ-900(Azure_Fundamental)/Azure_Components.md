# azure_msa_demo   
Cloud base MSA환경구성


# 목표
1) 클라우드 PaaS - Kubernetis 환경 구성
2) 1번의 환경에 대한 Apache Skywalking 모니터링 툴 적용


# 활용기술
   - Spring Boot
   - Docker
   - Kubernetis
   - Azure - AKS [Azure Kubernetis Service]
   - Azure - MariaDB [PaaS]


# 목차
1) Simple Spring Boot 프로젝트 생성
2) MariaDB와 연동하는 Simple Spring Boot 프로젝트 생성
3) Spring Boot App.을 Docker를 활용하여 이미지화
4) 2개의 Docker이미지를 Kubernetis환경에 배포
5) 1~4번의 과정을 Azure Platform 상에서 진행

## 1) Simple Spring Boot 프로젝트 생성
[참고 : https://spring.io/quickstart]

### 1-1. https://start.spring.io/ 접속
   * 아래와 같이 설정 후 GENERATE 클릭
   ![Alt text](capture/springBootStarter.png "Optional title")

### 1-2. demoA프로젝트를 Eclipse workspace에 압축해제 후 import

### 3-4. Push Local image to Docker Hub

   * Docker Hub에 이미지를 올리고 싶을 경우, 이미지명 형식을 Docker Hub와 맞춰 주어야 한다.
   * 이미지명의 형식은 [Doker Hub계정]/[Docker Hub Repo]:[태그명]
   	
	docker build -t flghdud1234/msa_test:demo .
	docker push flghdud1234/msa_test:demo
   
   * Docker Hub에 업로드한 이미지는 Docker Hub 웹사이트를 통해서도 확인할 수 있다.
   ![Alt text](capture/dockerHub1.png "Optional title")	

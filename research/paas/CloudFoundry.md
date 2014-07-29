# OverView
VM-Ware에서 개발되어 공표된 최초의 open paas

# Architecture

## Components
* Router : 모든 요청이 거쳐가는 곳으로 적절한 모듈로 분배하는데 일반적으로는 컨트롤러나 실행환경(DEA)으로 보내
* Authentication : 인증서버와 로그인서버가 함 IDM을 제공
* Cloud Controller : APP의 라이프사이클 관리 - 들어온 APP 자체의 바이너리 뿐 아니라 실행시 필요한 메타데이터등을 기록하기위한 레코드를 만들고 실행환경(DEA)가 그 APP를 실행하다록 지시하기도 한다. 추가적 부가정보도 기록(orgs, spaces, services, service instances, user roles....) 
* HM9000 :
* Application Execution(DEA) :
* Blob Store : 
* Service Brokers :
* Message Bus :
* Logging and Statistics : 
 



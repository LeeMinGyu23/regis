# 사원 관리 프로그램
프로젝트 기간 2022.11.07~2022.11.09

# 프로젝트의 목적
사원 레벨에 달라지는 사원정보 등록 시스템 및 마이페이지에서 회원정보 수정

#
프로젝트 개발 환경

**개발 환경**

+ Server : Apache Tomcat 8.5
+ DB : Oracle11g R2 (RDB)
+ Language : JAVA, Javascript, HTML5, CSS3 ,JSTL
+ Tool : Eclipse, GitHub, SQL Developer

# 내용

**구현 기능**

* 로그인
    - 운영자, 일반회원 로그인 기능 구현
    
* 사원등록
    - 로그인 후 레벨에 달라지는 사원정보 등록 시스템
        
* 마이페이지
    - 회원 정보 수정을 위한 시스템
    
**엔티티 그래프**    

![image](https://user-images.githubusercontent.com/117800561/202645537-4b961630-99a4-4dde-9a8d-5ac3bf8b62fa.png)

**용어 정의**

![image](https://user-images.githubusercontent.com/117800561/202645598-f2a87120-fdb2-46b9-bb97-488e6188c90e.png)
![image](https://user-images.githubusercontent.com/117800561/202645666-123fc828-965d-4a04-b65d-e3f7f1f3913e.png)
![image](https://user-images.githubusercontent.com/117800561/202645721-b55768f0-d782-41df-9953-f1ede8057228.png)

구현
![image](https://user-images.githubusercontent.com/117800561/202645826-41061cc6-2beb-4beb-943e-df4fe7a6c1bc.png)
![image](https://user-images.githubusercontent.com/117800561/202645867-d2630246-78a8-46cf-86ce-b15d2ccd03fa.png)
![image](https://user-images.githubusercontent.com/117800561/202645902-13c3509b-d45c-4b68-8aeb-22feda217af4.png)
![image](https://user-images.githubusercontent.com/117800561/202645968-5a9e19e3-59ad-4304-b418-b978c0d82752.png)

**로그인 인증**

사용자 인증시 사용되는 메소드
![image](https://user-images.githubusercontent.com/117800561/202646402-0f4f76e0-886b-44db-a4d9-a8be9764bdf4.png)
![image](https://user-images.githubusercontent.com/117800561/202646463-ec91be26-5350-42c6-b99b-3c9568ffe8ec.png)

아이디로 회원정보 가져오는 메소드
![image](https://user-images.githubusercontent.com/117800561/202646566-0c29c279-7f8e-4feb-b425-00bc227a8600.png)

서블릿
![image](https://user-images.githubusercontent.com/117800561/202646630-cee561f0-832f-492d-a6dc-c52b61c85bbf.png)
![image](https://user-images.githubusercontent.com/117800561/202646690-abd3238e-a219-4419-9da1-6b26f1c16f3b.png)

**회원정보 변경**
![image](https://user-images.githubusercontent.com/117800561/202646758-cb25ea5f-152b-4777-a54e-c28f163bf2d8.png)

서블릿 
![image](https://user-images.githubusercontent.com/117800561/202646849-45c35270-32e6-4fb7-8c14-6ba9c0489057.png)
![image](https://user-images.githubusercontent.com/117800561/202646928-bc7b7ea3-8a71-451d-9a00-6a30db3b86a7.png)

**사원정보 등록**
![image](https://user-images.githubusercontent.com/117800561/202647000-1baf4342-5f59-411f-b894-a3f15532d5c9.png)

서블릿
![image](https://user-images.githubusercontent.com/117800561/202647079-86e266bf-5f0b-4c04-8c64-90fd47fa1405.png)
![image](https://user-images.githubusercontent.com/117800561/202647117-00e6af95-9206-4a11-9264-34138c1c0a72.png)


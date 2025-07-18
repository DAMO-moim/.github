# 다모
<p align="center">
  <img src="https://github.com/user-attachments/assets/d54710a8-8396-4158-b0fc-aee0f6c7263e" alt="다모_로고" width="600" />
</p>

<p align="center">
  <strong>다모(DAMO)</strong>는 다양한 관심사를 가진 사용자들이 손쉽게 모임을 만들고 참여할 수 있는 <strong>모임 중심 소셜 플랫폼</strong>입니다.<br />
  카테고리 기반 모임 시스템과 함께, <strong>실시간 채팅</strong>, <strong>달력 기반 일정 관리</strong>, <strong>카테고리별 모임 분류</strong> 기능을 통해<br />
  사용자 간의 자연스러운 교류와 소통을 유도하고, 보다 생동감 있는 오프라인 연결을 지원합니다.
</p>

## 🚩 개요
- **프로젝트 이름** : DAMO  
- **프로젝트 기간** : 2025.03.12 ~ 2025.04.01  

<br><br>

## 🛠️ 기술 스택

### Frontend
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=React%20Query&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20Web%20Tokens&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)

### Infra & DevOps
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=white)

### Common
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black)

### Tools
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-8C4FFF?style=for-the-badge&logo=IntelliJ%20IDEA&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-F5F5F5?style=for-the-badge&logo=Notion&logoColor=black)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white)

<br><br>

## 📄 사용자 요구사항 정의서
[DAMO-요구사항_정의서](https://docs.google.com/spreadsheets/d/1qlGN1gRkRo5ejUh2xNh5vVb8woA3H6B37oJNfeGfbZY/edit?gid=0#gid=0)  

<br><br>

## 📄 API 문서 (Swagger)
[DAMO_API문서_Swagger](http://ec2-3-37-55-53.ap-northeast-2.compute.amazonaws.com:8080/swagger-ui/index.html#/)

<br><br>

## 🧩 ERD
<img width="1465" height="772" alt="다모_ERD" src="https://github.com/user-attachments/assets/6527c9a6-e02c-4cc4-8daa-c5033358e9bd" />


<br><br>

## ✨ 주요 기능

**1. 회원가입 및 로그인**  
- 이메일 인증 기반 회원가입  
- JWT 기반 로그인 및 인증  
- 로그인 실패 시 알림 제공  

**2. 관심사 기반 모임 생성/참여**  
- 카테고리별 모임 생성 및 참여 기능  
- 모임 소개, 일정, 최대 인원 설정  

**3. 실시간 채팅**  
- WebSocket + STOMP 기반 실시간 채팅 구현  
- 카테고리 채팅방 참여 및 구독  

**4. 스케줄 관리 기능**  
- 달력 기반 일정 확인  
- 단일/연속/정기 일정 등록  
- 일정 참여자 수 확인 가능  

**5. 마이페이지**  
- 내가 만든 모임, 참여한 모임 확인  
- 프로필 및 내 정보 수정 가능  

<br><br>

## 🤝 프로젝트 인원

| 채현후 | 홍성민 | 송호근 | 권택현 |
|--------|--------|--------|--------|
| <팀장><br/>FrontEnd | <팀원><br/> FrontEnd | <팀원><br/> BackEnd | <팀원><br/> BackEnd |

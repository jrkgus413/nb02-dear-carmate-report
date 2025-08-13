# Dear Carmate 프로젝트 완료 보고서

**프로젝트 이름**: Dear Carmate  
**작성자 / 팀**: 조가현 / 1팀  
**작성일**: 2025-08-13  

---

## 목차

- [1. 프로젝트 개요](#1-프로젝트-개요)  
- [2. 기술 스택 및 구조](#2-기술-스택-및-구조)  
- [3. 역할 및 책임 (R&R)](#3-역할-및-책임-rnr)  
- [4. 시행착오 및 해결 과정](#4-시행착오-및-해결-과정)  
- [5. 성과 및 회고](#5-성과-및-회고)  
- [6. 향후 계획 및 제언](#6-향후-계획-및-제언)  
- [7. 부록 / 참고 자료](#7-부록--참고-자료)  

---

## 1. 프로젝트 개요

- **목적**: 중고차 판매현장에서 발생하는 계약, 차량, 고객 관리를 한 곳에서 지원하는 통합 시스템
- **기간**: 2025‑07‑22 ~ 2025‑08‑13
- **핵심 기능**:
  - 인증/회원관리 (Authentication / User Management)
  - 차량 관리 (Car Management)
  - 고객 관리 (Customer Management)
  - 계약 관리 (Contract Management)
  - 대시보드 (Dashboard)
  - 계약서 관리 (Contract Document Handling)
  - 대용량 업로드 (Bulk Upload)  

---

## 2. 기술 스택 및 아키텍처  
- **Backend**: node.js, express.js, TypeScript, tsc, nodemon, jsonwebtoken, bcrypt, multer, ts-node, cookie‑parser, dotenv, Prisma (ORM)  
- **Database**: PostgreSQL  
- **API 문서화**: Swagger  
- **협업 도구**: GitHub, Git  
- **일정/이슈 관리**: Git Issue, Notion  
- **배포**: Backend – Render, Repository – GitHub  

---

## 3. 역할 및 책임 (Roles & Responsibilities)

### Back-End
- **유저**: 정보 조회 및 수정
- **회사**: 등록, 목록 조회, 유저 목록 조회, 수정, 삭제
- **대시보드**: 전반적인 데이터 시각화 및 통계 제공
- **Bigint 타입 변환 전역 처리**

### Front-End
- UI 개선: 회원탈퇴 기능 구현

### 환경 및 역할
- **Back‑End 서버**: Render를 통한 배포
- **저장소**: Gitbub Repository
- **프로젝트 관리**: PM 역할 수행, 중간 및 최종 발표 등  

---

## 4. 주요 도전과 해결 과정 (Challenges & Resolutions)
- **Prisma에서 통계 함수 사용의 낯설음**  
  → ORM 문법이 익숙치 않아 초기 어려움 있었음.  
  → 다양한 예제 학습 및 로그 확인을 통한 단계별 이해로 해결.  

- **Render를 통한 빌드/배포 오류**  
  → 초기 설정 오류로 배포 실패가 다수 발생.  
  → 명령어 순서와 에러 메시지 분석을 통해 수정, 팀워크로 해결.

---

## 5. 성과 및 회고 (Results & Retrospective)

### 주요 성과  
- **일정 준수**: 계획 대비 100% 일정 달성  
- **기능 완성도**: 모든 핵심 기능 정상 작동 및 발표 시 시연 성공  

### 개선 여지  
- **진행 모니터링 강화 필요**: 팀원별 진행 상황에 대한 실시간 확인 부족  
- **역량 기반 분업 부족**: 구성원 역량 고려한 작업 분배 아쉬움  


### 배운 점  
- **협업과 개인 학습의 균형 중요성 인식**  
- **문서화 및 협업 워크플로우의 중요성 체감**

---

## 6. 향후 계획 및 제언 (Future Work)
- **기술 리팩토링**  
  - 모듈화: 공통 코드 분리  
  - 중복 제거 및 구조 최적화  
  - 유지보수성 및 확장성 향상 기대  

- **작업 관리 개선**  
  - 팀원별 **간단한 진행 가시성 확보** 방안 수립  
  - **역량 기반 작업 분배** 체계화 고려  

---

## 7. 부록 / 참고 자료 (Appendix / References)

- **GitHub 저장소**: https://github.com/jrkgus413/nb2-dearcarmate‑team1  
- [Dear Carmate 시연영상](https://file.notion.so/f/f/a29b669d-e680-438e-b18c-08888fc54a21/2a51be65-35b2-493f-9fbe-441274b1a841/nb02-dear-carmate.mp4?table=block&id=24c6fd22-8e8d-8122-9baa-dce2875d5ac6&spaceId=a29b669d-e680-438e-b18c-08888fc54a21&expirationTimestamp=1755100800000&signature=OnkjaTc0UBDNyf5mVOVEJt3beNM9z_eqrr4uwWu1cIY&downloadName=nb02-dear-carmate.mp4)
- **API 문서 / 관리 문서**:
  - [프로젝트 계획서] (https://www.notion.so/238ddc684deb810d9d0ef0441ee3ff76?source=copy_link)
  - [프로젝트 관리 문서] (https://github.com/jrkgus413/nb2-dearcarmate-team1/wiki)
  - 배포 주소:
    - 백엔드: https://nb2-dearcarmate‑team1.onrender.com/  
    - 프론트엔드: https://www.nb02-dearcarmate.online/signin  

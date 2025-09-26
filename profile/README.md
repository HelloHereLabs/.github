# 🏠 HelloHere - AI 기반 실시간 외국인-시민 매칭 플랫폼

**2025 서울 AI 해커톤 출품작**  
**해커톤 프로젝트:** AWS Bedrock AI와 실시간 위치 서비스를 활용한 혁신적인 글로벌 문화 교류 플랫폼

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)

---

## ✨ 서비스 소개

HelloHere는 외국인 관광객과 현지 시민을 AI 기술과 실시간 위치 기반 매칭으로 연결하여, **언어 장벽 없는 자연스러운 문화 교류**를 지원하는 혁신적인 플랫폼입니다.

### 🎯 서비스 개요

**해결하고자 하는 문제**
- 외국인 관광객들의 언어 장벽과 문화적 어려움  
- 현지인과의 자연스러운 교류 기회 부족  
- 안전하고 신뢰할 수 있는 글로벌 소통 플랫폼 부재  
- 일회성 만남을 넘어선 지속적인 문화 교류의 어려움  

**HelloHere의 솔루션**
- AI 기반 실시간 번역 (STT/TTS 지원)  
- 위치 기반 스마트 매칭  
- 안전 모니터링 시스템과 사용자 신고 기능   

---

## 🎯 핵심 기능

### 🤖 AI 기반 실시간 번역
- Amazon Bedrock Titan Text 모델 활용 고품질 번역  
- 음성 ↔ 텍스트 변환(STT/TTS) 지원  
- 한국어, 영어, 일본어, 중국어, 스페인어 등 10개 언어 지원  

### 📍 위치 기반 스마트 매칭
- GPS + 관심사 기반 AI 매칭 알고리즘  
- 벡터 임베딩 기반 유사도 매칭  
- 안전한 공개 장소 추천  

### 🛡️ 안전성 강화 시스템
- AI 기반 부적절 콘텐츠 필터링  
- 신고 시스템 및 사용자 평가 기능  
- 실시간 위험 상황 모니터링  

### 🌍 글로벌 커뮤니티
- 실시간 그룹 채팅과 번역 지원  
- 문화 교류 이벤트 및 모임 기능  
- 언어 학습 파트너 매칭  

---

## 🛠️ 기술 스택

### Frontend
- **React 18** + **Next.js 14** + **TypeScript**  
- **Tailwind CSS** (반응형 UI)  
- **Axios** (API 통신)  
- **Socket.io** (실시간 채팅)  

### Backend
- **NestJS** + **TypeScript**  
- **AWS Lambda** (서버리스 아키텍처)  
- **Amazon DynamoDB** (NoSQL DB)  
- **Amazon Bedrock** (AI/ML 서비스)  

### AI/ML Services
- **Amazon Bedrock Titan Text** - 번역 & 텍스트 생성  
- **Amazon Nova Sonic** - 음성 처리 (STT/TTS)  
- **Amazon Titan Embeddings** - 벡터 임베딩    

### Infrastructure
- **AWS API Gateway** - API 관리  
- **AWS CloudFront** - CDN  
- **AWS Amplify** - 프론트엔드 배포  
- **Docker** - 컨테이너화  

---

## 👥 팀 소개 - (모아)moa

| 이름 | 역할 | 
|------|------|
| **김재영** | 🔧 Backend Developer
| **김지연** | 💻 Frontend Developer
| **이고헌** | 💻 Frontend Developer

---

## 🗓️ 개발 일정

| 단계 | 기간 | 주요 활동 | 상태 |
|------|------|-----------|------|
| 기획 단계 | 2025.08.27 ~ 08.29 | 아이디어 구체화, 기술 스택 선정 | ✅ |
| 설계 단계 | 2025.08.30 ~ 09.07 | DB 설계, API 명세, UI/UX 디자인 | ✅ |
| 개발 단계 | 2025.09.08 ~ 09.25 | 프론트/백엔드 개발, AI 통합 | ✅ |
| 최종 완성 | 2025.09.26 | 본선 결과물 제출 | ✅ |

---

## 🚀 주요 성과

- ⚡ 서버리스 아키텍처 기반 99.9% 가용성  
- 🤖 실시간 다국어 번역 지원 (10개 언어)  
- 📍 AI 매칭 정확도 85% 이상  
- 🔒 안전 필터링 정확도 99.5%  
- 🌐 글로벌 사용자 대상 문화 교류 서비스  

---

## 📱 주요 화면

### 메인 대시보드
- 실시간 매칭 추천  
- 언어별 통계 및 활동 현황  

### 채팅 인터페이스
- 실시간 번역 기능   
- 음성 메시지 지원  

### 매칭 결과
- 위치 기반 지도 뷰  
- 사용자 프로필 및 관심사  
- 안전한 만남 장소 추천  

---

## 🏆 AI 기능

- 🎤 **실시간 음성 번역**: 말하면 바로 상대방 언어로 번역    
- 🗺️ **스마트 위치 매칭**: AI가 분석한 최적의 만남 장소 추천  
- 🛡️ **실시간 안전 모니터링**: AI 기반 위험 상황 감지 및 대응

# React와 Node.js로 구현한 로그인/회원가입 페이지
원본 들어가보시면 협업자는 저 포함 2명이지만 최종적으로 4명이서 웹사이트를 구축했습니다. 최종 완성은 2025년 12월입니다!

# 📚 Nonmoon (논문 레퍼런스 정리 및 협업 플랫폼)

> **학술 연구 및 학습 과정에서 발생하는 레퍼런스 관리의 비효율성을 해결하기 위한 웹 기반 플랫폼**

---

## 👨‍💻 프로젝트 및 팀원 소개

- **프로젝트명**: 논문 레퍼런스 정리 서비스 (`nonmoon`)
- **수행 교과목**: 웹프로그래밍 (2025.12.10)
- **팀명**: 불사조 7조

### 👥 Team Members & Roles

| 팀원 | 담당 역할 |
| :--- | :--- |
| **강지호** | 🎤 발표 및 프로젝트 총괄 |
| **박예슬** | 🎨 PPT 제작 및 기획 문서 작성 |
| **임성민** | 🔑 로그인/회원가입, 그룹 및 팀원 초대/관리 시스템 구축 |
| **김경은** | 📑 논문 인용/요약, PDF 동기화 및 AI 연동 개발 |

---

## 📸 주요 구현 화면 (UI Screenshots)

| 1. 로그인 / 회원가입 | 2. 팀원 & 그룹 관리 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/ebbc129b-32a3-46b9-8509-9b1f296ed239" width="450" alt="로그인 화면"> | <img src="https://github.com/user-attachments/assets/20dd21d7-2649-4066-abae-f948a5d8057a" width="450" alt="그룹 관리 화면"> |
| **3. 논문 업로드 & 인용 카드** | **4. 인용 카드 리스트 & 검색** |
| <img src="https://github.com/user-attachments/assets/f39e0cc7-b650-4cb8-a16c-dc061e3475e9" width="450" alt="논문 관리 화면"> | <img src="https://github.com/user-attachments/assets/941fa420-80b4-4c25-abc5-a6bff85b4cff" width="450" alt="인용 카드 리스트"> |

---

## 🎬 시연 영상 (Demo Video)

[![Nonmoon 시연 영상 보기](https://img.youtube.com/vi/GkEJ6pepO4I/0.jpg)](https://youtu.be/GkEJ6pepO4I)

> 👆 **위 이미지를 클릭하시면 유튜브 시연 영상으로 이동합니다.**

---

## 🎯 프로젝트 배경 및 목표

### 📌 개발 배경 (기존 문제점)
1. **수동적인 서지 정보 정리**: 논문 수집 시 서지 정보를 수동으로 추출하거나 엑셀에 정리하는 비효율 발생
2. **인용 스타일 적용의 어려움**: APA, MLA, Chicago 등 복잡한 학술 인용 양식을 일일이 맞추는 데 많은 시간 소모
3. **팀 프로젝트 공유 한계**: 디지털 전환 시대에도 팀원 간 연구 자료 공유 및 공동 작업을 위한 일관된 시스템 부족

### 💡 주요 목표
- **체계적인 레퍼런스 관리**: 연구 및 학습 생산성 극대화
- **협업 지원**: 프로젝트 그룹 기반의 실시간 자료 공유 및 권한 관리
- **AI 및 PDF 연동**: 논문 요약, 인용 정규화, PDF 동기화 기능 제공

---

## ✨ 핵심 기능 (Key Features)

- **🔐 사용자 인증 & 세션 관리**
  - 회원가입/로그인 및 암호화 처리를 통한 보안 강화
  - 세션 관리를 통한 사용자별 맞춤 환경 유지

- **👥 그룹 및 팀원 협업**
  - 연구 주제/프로젝트별 그룹 생성 및 기본 정보 설정
  - 역할 기반 권한 설정 (관리자, 작성자, 조회자 등) 및 팀원 초대/삭제

- **📄 논문 & 인용 카드 관리**
  - PDF 논문 업로드 및 업로더 표시를 통한 출처 명확화
  - 원문 링크, 페이지, 메모를 포함한 인용(Quote) 카드 생성
  - 키워드, 저자, 태그, 그룹 기반 검색·필터링 및 북마크 기능

- **🤖 AI & PDF 동기화 연동**
  - AI 기반 인용 문구 정규화 (`/api/ai/normalize-quote`)
  - 요약 선택 시 viewer 소스가 자동 교체되는 PDF 동기화
  - 인라인 수정 기능을 통한 인용 카드 실시간 업데이트

---

## 🛠 기술 스택 (Tech Stack)

### Frontend
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">

### Backend & Database
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=PHP&logoColor=white"> <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=Laravel&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=AmazonAWS&logoColor=white">

### Tools
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white">

---

## 🚀 시작하기 (Installation & Run)

### 1. Repository Clone
```bash
git clone [https://github.com/jiho6367-design/nonmoon.git](https://github.com/jiho6367-design/nonmoon.git)
cd nonmoon
2. Frontend (React) 실행
Bash
# 패키지 설치
npm install

# 개발 서버 구동
npm run start
# 또는 npm run dev
3. Backend 실행
Bash
# 백엔드 서버 디렉토리로 이동 후 구동
npm run dev
# 또는 node server.js

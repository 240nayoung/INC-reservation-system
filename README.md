# 🍽️ 식당 예약 서비스

## 📌 소개  
React와 Flask를 활용한 **웹 기반 식당 예약 서비스**입니다.  
사용자는 예약 가능한 테이블 현황을 간편하게 확인하고, 식당 예약을 진행할 수 있습니다.

## 팀원
| 이름 | 역할 |
|------|------|
| 최민경 @LylaDev | 풀스택 개발 (프론트엔드 & 백엔드) |
| 이나영 @240nayoung | 풀스택 개발 (프론트엔드 & 백엔드) |

## 🛠️ 기술 스택
- **Frontend**: React
- **Backend**: Flask
  
## 🚀 주요 기능
- 레스토랑의 예약 가능한 테이블 현황 확인
- 원하는 날짜, 시간, 테이블 종류 선택하여 예약
- 예약 현황 확인
- 원하지 않는 예약 삭제

## 👩‍💻 개인 기여 및 담당 역할 (@240nayoung)
### Frontend (React)
- 메인 페이지 및 공통 페이지 레이아웃 구현
- 팝업 UI 구현
- 예약 페이지 및 예약 정보 입력 UI 구현

### Backend (Flask)
- 식당 예약 기능 구현
- 예약자 정보 입력 기능 구현 및 프론트엔드 연동

[개인 Pull Request 내역] (https://github.com/Lyla-Dev/INC-reservation-system/pulls?q=is%3Apr+author%3A240nayoung)

## 📁 프로젝트 구조
```
INC-reservation-system/
├── backend/
│   ├── migrations/
│   ├── src/
│   │   ├── database/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── app.py
│   └── data/
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── LogIn/
│   │   │   ├── MainPage/
│   │   │   ├── PageLayout/
│   │   │   ├── Popup/
│   │   │   ├── Reservation/
│   │   │   ├── ReservationInfo/
│   │   │   ├── ReservationStatus/
│   │   │   └── SignUp/
│   │   ├── fonts/
│   │   ├── App.css
│   │   ├── App.jsx
│   ├── README.md
│   └── .gitignore
└── README.md 
```

## 🖇️ 원본 리포지터리
2인 팀 공동 개발 프로젝트로, 개인 포트폴리오 정리를 위해 Fork한 리포지터리입니다. 
[Original Repository] (https://github.com/Lyla-Dev/INC-reservation-system)

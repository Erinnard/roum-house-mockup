# ROUM HOUSE Phase 1 Client Mockup

클라이언트 화면/기능 범위 합의용 인터랙티브 목업입니다.

## 포함 범위
- 회원 APP: HOME, Dynamic QR, 멤버십/Founder/Light, 코트 예약, 패들 Add-on, Open Play, 프로그램/레슨, Nourish Bar, MY/결제
- ADMIN: Dashboard, 회원/해지예정, 예약 캘린더, Open Play, 프로그램, 재고/Nourish Bar, 결제/매출, 운영 설정

## 제외/Phase 2 예시
- Android NFC / Apple Wallet
- Guest Invitation
- Paddle Storage 서버 기능
- 비회원 Play Experience
- 시설 신고
- Waitlist 자동화
- POS/키오스크/커피머신 연동

## 로컬 실행
정적 HTML이라 빌드 없이 실행 가능합니다.

```bash
python -m http.server 8080
```

브라우저에서 `http://localhost:8080` 접속.

## GitHub Pages
이 저장소에는 GitHub Pages용 workflow가 포함되어 있습니다.
Repository > Settings > Pages > Build and deployment에서 **GitHub Actions**를 선택하면 main push 시 배포할 수 있습니다.

> 모든 데이터와 결제/예약 동작은 샘플입니다. 실제 Toss Payments, Spring Boot API, QR Reader와 연결되어 있지 않습니다.

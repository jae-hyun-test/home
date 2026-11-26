# My Investment Dashboard

개인 주식 투자 현황을 관리하기 위한 정적 웹 대시보드입니다.

## 주요 기능
- 총 평가금액, 투자 원금, 평가손익 및 수익률
- 보유 종목 추가 / 수정 / 삭제
- 종목별 포트폴리오 비중 차트
- 브라우저 localStorage에 데이터 저장
- 모바일 반응형 화면
- GitHub Actions를 통한 GitHub Pages 배포

## 파일 구조
```
.
├── index.html
├── assets/
│   ├── app.js
│   └── style.css
└── .github/
    └── workflows/
        └── pages.yml
```

## GitHub Pages 활성화
1. GitHub 저장소의 **Settings → Pages**로 이동합니다.
2. **Build and deployment → Source**에서 **GitHub Actions**를 선택합니다.
3. `main` 브랜치에 변경사항을 push하면 Actions가 사이트를 배포합니다.
4. 저장소의 **Actions** 탭에서 `Deploy investment dashboard to GitHub Pages` 실행 결과를 확인합니다.
5. 배포가 완료되면 **Settings → Pages**에 표시되는 사이트 주소로 접속합니다.

## 데이터 안내
현재 등록된 종목과 가격은 화면 확인을 위한 예시 데이터입니다. 실시간 시세가 아닙니다.
종목을 추가하거나 수정한 데이터는 현재 사용 중인 브라우저의 localStorage에 저장됩니다. 다른 브라우저나 기기와 자동 동기화되지 않습니다.

## 주의
이 프로젝트는 개인 기록용 도구이며 투자 추천이나 매매 신호를 제공하지 않습니다.

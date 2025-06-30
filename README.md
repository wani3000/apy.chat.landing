# Halo - AI Studio Website

이 프로젝트는 Framer 템플릿을 기반으로 한 Halo AI Studio 웹사이트의 완전한 로컬 구현입니다.

## 🚀 특징

- **반응형 디자인**: 모든 디바이스에서 완벽하게 작동
- **모던 UI/UX**: 최신 웹 디자인 트렌드 적용
- **인터랙티브 요소**: 부드러운 애니메이션과 전환 효과
- **완전한 기능**: 원본 Framer 웹사이트의 모든 섹션 구현

## 📁 파일 구조

```
├── index.html          # 메인 HTML 파일
├── styles.css          # CSS 스타일시트
├── script.js           # JavaScript 기능
└── README.md           # 이 파일
```

## 🛠 사용 방법

### 1. 로컬 서버로 실행 (권장)

**Python 서버 사용:**
```bash
python3 -m http.server 8000
```

**Node.js 서버 사용:**
```bash
npx serve .
```

**PHP 서버 사용:**
```bash
php -S localhost:8000
```

### 2. 브라우저에서 확인

서버 실행 후 브라우저에서 다음 주소로 접속:
- http://localhost:8000

### 3. 직접 파일 열기

HTML 파일을 직접 브라우저에서 열 수도 있지만, 일부 기능이 제한될 수 있습니다.

## 🎨 섹션 구성

1. **네비게이션**: 고정 헤더 메뉴
2. **히어로**: 메인 제목과 CTA 버튼
3. **서비스**: AI 솔루션 소개
   - Chatbot Development
   - Content Creation
   - Workflow Automations
   - LLM Development
   - AI Consulting
4. **프로세스**: 3단계 작업 과정
5. **통계**: 회사 성과 수치
6. **팀**: 팀 멤버 소개
7. **가격**: 구독 플랜 (월간/연간)
8. **리뷰**: 고객 후기
9. **FAQ**: 자주 묻는 질문
10. **연락처**: 연락 정보 및 폼
11. **푸터**: 소셜 링크 및 추가 정보

## ⚡ 주요 기능

### JavaScript 기능
- 부드러운 스크롤 네비게이션
- FAQ 아코디언
- 가격 토글 (월간/연간)
- 폼 제출 처리
- 실시간 시간 표시
- 스크롤 애니메이션
- 통계 숫자 카운터 애니메이션

### CSS 특징
- 그라데이션 배경
- 호버 효과
- 전환 애니메이션
- 반응형 그리드
- 플렉스박스 레이아웃
- 블러 효과

## 🎯 브라우저 호환성

- Chrome (최신)
- Firefox (최신)
- Safari (최신)
- Edge (최신)

## 📱 반응형 브레이크포인트

- 데스크톱: 1200px+
- 태블릿: 768px - 1199px
- 모바일: ~767px

## 🔧 커스터마이징

### 색상 변경
`styles.css` 파일에서 CSS 변수를 수정하여 색상을 변경할 수 있습니다:

```css
:root {
  --primary-color: #667eea;
  --secondary-color: #764ba2;
  --text-color: #333;
  --background-color: #f8fafc;
}
```

### 콘텐츠 수정
`index.html` 파일에서 텍스트, 이미지, 링크를 직접 수정할 수 있습니다.

### 기능 추가
`script.js` 파일에서 추가 JavaScript 기능을 구현할 수 있습니다.

## 📞 지원

문의사항이 있으시면 다음으로 연락해주세요:
- Email: info@halo.com
- Phone: +31 (0) 20 343 9223

## 📄 라이선스

Template by Tibor Bregman - BlueStar Supply
© 2025, Halo Inc - All rights reserved.

---

**참고**: 이 웹사이트는 Framer 템플릿을 기반으로 한 교육/개발 목적의 구현입니다.

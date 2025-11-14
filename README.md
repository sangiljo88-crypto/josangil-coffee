# ☕ 조상일 커피 - 공식 웹사이트

> 12년 경력 국제 대회 수상 바리스타의 프리미엄 스페셜티 커피

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/josangil-coffee/deploys)

## 🎯 프로젝트 소개

**조상일 커피**는 2023년 엘살바도르 핸드드립 챔피언십 준우승 바리스타가 직접 운영하는 프리미엄 스페셜티 커피 브랜드입니다.

### 핵심 USP
- 🏆 국제 대회 수상 (준우승)
- ⚗️ 세계 최초 드립에센스 기술
- ⏰ 시간 철학 기반 커피 블렌딩
- 📦 국내 최초 20g 대용량 드립백
- 💼 대기업 128회 커피 교육

---

## 🚀 빠른 시작

### 웹사이트 보기
👉 **[조상일 커피 공식 사이트](https://josangil-coffee.netlify.app)**

### 로컬에서 실행
```bash
# 1. 저장소 복제
git clone https://github.com/your-username/josangil-coffee.git

# 2. 폴더 이동
cd josangil-coffee

# 3. index.html 파일을 브라우저에서 열기
# (더블클릭 또는 Live Server 확장 사용)
```

---

## 📁 프로젝트 구조

```
josangil-coffee/
├── index.html              # 메인 페이지
├── README.md              # 이 파일
├── 배포_가이드.md          # GitHub/Netlify 배포 가이드
└── images/                # 이미지 폴더
    ├── josangil_profile.jpg
    ├── product_beans_01.jpg
    ├── product_dripbag_01.jpg
    ├── product_essence_01.jpg
    ├── award_elsalvador.jpg
    ├── education_hyundai.jpg
    ├── workspace_roasting.jpg
    ├── workspace_handpick.jpg
    └── review_01.jpg
```

---

## 🎨 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **호스팅**: Netlify
- **버전 관리**: GitHub
- **DB 수집**: Google Sheets + Apps Script
- **알림**: Email (Gmail API)

---

## 📊 주요 기능

### 1. 반응형 디자인
- ✅ 데스크톱 (1200px+)
- ✅ 태블릿 (768px ~ 1199px)
- ✅ 모바일 (~ 767px)

### 2. 파소나(PASONA) 프레임워크 적용
- **P**roblem: 6가지 고객 고민 제시
- **A**gitation: 감정적 공감대 형성
- **S**olution: 전문성 증명 (수상, 경력)
- **O**ffer: 3가지 제품 라인업
- **N**arrow: 희소성 & 긴급성
- **A**ction: 다중 전환 경로

### 3. 전환 최적화
- 고정 헤더 CTA
- 플로팅 버튼 (전화 + 카톡)
- 섹션별 CTA
- 문의 폼 (구글 시트 자동 수집)

### 4. SEO 최적화
- Semantic HTML
- Meta 태그 완비
- 모바일 최적화
- 빠른 로딩 속도

---

## 🔧 설정 방법

### 1. 구글 시트 DB 연동

**상세 가이드**: `구글시트_연동_가이드.md` 참고

간단 요약:
```javascript
// index.html 파일에서 수정
const SCRIPT_URL = 'https://script.google.com/macros/s/YOUR_SCRIPT_ID/exec';
// → 실제 배포 URL로 변경
```

### 2. 이미지 추가/변경

```bash
# images 폴더에 이미지 추가
images/
  └── your-new-image.jpg

# HTML에서 참조
<img src="images/your-new-image.jpg" alt="설명">
```

### 3. 내용 수정

**연락처 변경**:
```html
<!-- 전화번호 -->
<a href="tel:031-392-2048">031-392-2048</a>

<!-- 카카오톡 -->
<a href="http://pf.kakao.com/_xmGaIn">조상일커피 본점</a>
```

**제품 가격 변경**:
```html
<div class="price">
    <strong>13,900원~</strong> / 200g
</div>
```

---

## 🚀 배포하기

### Netlify로 배포 (추천)

**상세 가이드**: `배포_가이드.md` 참고

**3단계 배포**:
```
1. GitHub에 푸시
2. Netlify 계정 연동
3. 자동 배포 완료! 🎉
```

**예상 소요 시간**: 10분

---

## 📈 성능 & 품질

### Lighthouse 점수 목표
- 🟢 Performance: 90+
- 🟢 Accessibility: 95+
- 🟢 Best Practices: 95+
- 🟢 SEO: 100

### 브라우저 지원
- ✅ Chrome (최신)
- ✅ Firefox (최신)
- ✅ Safari (최신)
- ✅ Edge (최신)
- ✅ 모바일 브라우저

---

## 🎯 전환율 최적화

### 현재 적용된 기법

1. **첫 3초 후킹**
   - "커피 맛이 다 거기서 거기?" (공감형 카피)

2. **신뢰도 구축**
   - 국제 대회 수상 배지
   - 구체적 수치 (12년, 45톤, 128회, 99%)
   - 대기업 교육 경력

3. **차별화 강조**
   - 세계 최초 드립에센스
   - 시간 철학 포지셔닝
   - 가격 비교 (1/3)

4. **긴박감 조성**
   - 하루 생산량 제한
   - 우선 배정 혜택

5. **마찰 제거**
   - 클릭투콜
   - 24시간 카톡
   - 간편 폼 (4개 필드)

### 예상 성과
- 일반 홈페이지: 1~2% 전환율
- **본 페이지 목표: 5~8%**

---

## 📞 연락처

### 조상일 커피
- **전화**: 031-392-2048
- **카카오톡**: [조상일커피 본점](http://pf.kakao.com/_xmGaIn)
- **주소**: 경기도 군포시 산본천로214번길 30, 2층
- **영업시간**: 평일 10:00 - 17:00

### 웹사이트 개발
- **제작**: 스피드랜딩 (brandforyou.kr)
- **이메일**: support@brandforyou.kr
- **서비스**: 랜딩페이지 전문 제작

---

## 📄 라이선스

© 2024 조상일 커피. All Rights Reserved.

**사용 권한**:
- ✅ 조상일 커피 공식 사이트로 사용
- ✅ 수정 및 커스터마이징
- ✅ 상업적 사용

**제한 사항**:
- ❌ 제3자 재판매 금지
- ❌ 타 브랜드 도용 금지
- ❌ 소스코드 무단 배포 금지

---

## 🙏 감사의 말

이 웹사이트는 **파소나(PASONA) 이론**과 **최홍희 상세페이지 기법**을 완벽히 적용하여 제작되었습니다.

조상일 바리스타님의 12년 경력과 국제 대회 수상 실력을 효과적으로 전달하기 위해 최선을 다했습니다.

**좋은 커피 사업 되시길 진심으로 응원합니다!** ☕✨

---

## 📚 추가 자료

- [배포 가이드](배포_가이드.md)
- [구글 시트 연동 가이드](../구글시트_연동_가이드.md)
- [이미지 추가 가이드](../이미지_추가_가이드.md)

---

**⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!**

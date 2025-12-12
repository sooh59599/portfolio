# 개발자 포트폴리오

순수 HTML, CSS, JavaScript로 제작된 모던하고 반응형인 개발자 포트폴리오 웹사이트입니다.

## 주요 기능

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기에서 완벽하게 작동
- **모던한 UI/UX**: 그라디언트, 애니메이션, 부드러운 전환 효과
- **인터랙티브**: 스크롤 애니메이션, 네비게이션 하이라이트, 스킬 바 애니메이션
- **빠른 로딩**: 별도의 빌드 과정 없이 바로 실행 가능

## 포함된 섹션

1. **Hero Section**: 메인 소개 및 CTA 버튼
2. **About**: 자기소개 및 개인 정보
3. **Skills**: 기술 스택을 카테고리별로 시각화
4. **Projects**: 프로젝트 포트폴리오 그리드
5. **Experience**: 경력 및 교육 타임라인
6. **Contact**: 연락처 정보 및 문의 폼

## 사용 방법

1. 웹 브라우저에서 `index.html` 파일을 열기
2. 또는 로컬 서버 실행:
   ```bash
   # Python 3가 설치되어 있는 경우
   python -m http.server 8000

   # Node.js가 설치되어 있는 경우
   npx http-server
   ```
3. 브라우저에서 `http://localhost:8000` 접속

## 커스터마이징

### 개인 정보 수정

`index.html` 파일을 열어 다음 정보를 수정하세요:

- 이름 및 소개 (Hero Section)
- 자기소개 및 연락처 (About Section)
- 기술 스택 및 숙련도 (Skills Section)
- 프로젝트 정보 (Projects Section)
- 경력 사항 (Experience Section)

### 색상 변경

`styles.css` 파일의 `:root` 섹션에서 색상 변수를 수정하세요:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... */
}
```

### 프로필 이미지 추가

About 섹션의 `.image-placeholder` 부분을 실제 이미지로 교체하세요:

```html
<div class="about-image">
    <img src="your-photo.jpg" alt="프로필 사진">
</div>
```

## 배포 방법

### GitHub Pages

1. GitHub 저장소에 코드 푸시
2. Settings > Pages
3. Source를 main branch로 설정
4. 배포 완료!

### Netlify

1. [Netlify](https://netlify.com)에 로그인
2. 저장소 연결 또는 폴더 드래그 앤 드롭
3. 자동 배포 완료!

### Vercel

1. [Vercel](https://vercel.com)에 로그인
2. Import Project
3. GitHub 저장소 선택
4. 배포 완료!

## 기술 스택

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Intersection Observer API
- CSS Variables

## 브라우저 지원

- Chrome (최신)
- Firefox (최신)
- Safari (최신)
- Edge (최신)

## 라이선스

자유롭게 사용, 수정, 배포 가능합니다.

---

Made with ❤️ using HTML, CSS, and JavaScript

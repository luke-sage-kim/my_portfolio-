# my_portfolio

김명현 백엔드 개발자 포트폴리오 (정적 HTML 단일 페이지).

## 보기

- `index.html`을 브라우저로 열면 바로 확인할 수 있습니다.
- GitHub Pages로 배포하면 루트의 `index.html`이 메인 페이지로 제공됩니다.

## 구성

- `index.html`: 페이지 전체 (CSS 인라인, 프로필 사진 base64 포함)
- 폰트: Pretendard (jsDelivr CDN)

## GitHub Pages 배포

1. 저장소 **Settings → Pages**로 이동합니다.
2. **Build and deployment → Source**를 **GitHub Actions**로 선택합니다.
3. `main` 브랜치에 push하면 `.github/workflows/pages.yml`이 자동으로 배포합니다.
4. 배포 주소: `https://luke-sage-kim.github.io/my_portfolio-/`

`.nojekyll` 파일은 Jekyll 처리를 끄기 위해 넣어 두었습니다.

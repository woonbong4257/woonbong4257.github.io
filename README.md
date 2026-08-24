# Research CV Website

GitHub Pages에 바로 배포할 수 있는 연구자용 CV 홈페이지입니다.

## 내용 수정하기

- 이름, 소개, 소속, 논문, 경력: `index.html`
- 색상, 글꼴, 레이아웃: `style.css`
- 메뉴, 등장 효과, 논문 필터: `script.js`
- 프로필 사진: `index.html`의 `.portrait-placeholder` 영역을 `<img>` 태그로 교체
- CV 파일: `assets/cv.pdf` 경로에 본인 PDF 추가
- 논문 및 SNS 링크: `href="#"`를 실제 주소로 교체

## GitHub Pages 배포

1. 이 폴더를 GitHub 저장소에 push합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Deploy from a branch**를 선택합니다.
4. `main` 브랜치와 `/ (root)` 폴더를 선택하고 저장합니다.

잠시 후 `https://사용자명.github.io/저장소명/` 주소로 공개됩니다.

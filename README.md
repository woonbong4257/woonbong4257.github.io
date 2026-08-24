# Researcher Website

GitHub Pages에서 바로 배포할 수 있는 연구자용 개인 홈페이지입니다. 큰 그라데이션 히어로와 어두운 카드 UI를 사용했으며, 프레임워크나 빌드 과정은 필요하지 않습니다.

## 구성

- `index.html`: Home, About, Blog 링크가 이어지는 단일 페이지
- `style.css`: 전체 디자인과 반응형 레이아웃
- `script.js`: 모바일 메뉴, 스크롤 효과, 현재 섹션 메뉴 표시

## 본인 정보로 바꾸기

프로젝트 전체에서 아래 예시 문구를 검색해 교체하세요.

- `김민준`, `MINJUN KIM`, `Minjun Kim`
- `OO대학교`
- `minjun.kim@example.com`
- `href="#"`로 되어 있는 논문, SNS, 최근 글 링크

프로필 사진은 `assets/profile.jpg`, CV는 `assets/cv.pdf`로 추가하세요. 사진을 넣은 후 `index.html`의 `.photo-placeholder`를 아래 코드로 교체하면 됩니다.

```html
<img src="assets/profile.jpg" alt="김민준 프로필 사진" />
```

## GitHub Pages 배포

1. 이 폴더를 GitHub 저장소에 push합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Deploy from a branch**를 선택합니다.
4. `main` 브랜치와 `/ (root)` 폴더를 선택하고 저장합니다.

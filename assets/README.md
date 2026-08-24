# Assets

이 폴더에 본인의 파일을 넣어 주세요.

- `cv.pdf`: 상단 **CV 다운로드** 버튼에 연결되는 이력서
- `profile.jpg`: 프로필 사진으로 사용할 이미지(선택)

프로필 사진을 사용할 때는 `index.html`의 `portrait-placeholder` 요소 안쪽을 아래와 같이 바꾸면 됩니다.

```html
<img src="assets/profile.jpg" alt="김민준 프로필 사진" />
```

그리고 `style.css`에 다음 스타일을 추가하세요.

```css
.portrait-placeholder img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

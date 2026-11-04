# 김준태 · snjune6

부산에서 작업하는 개발자 김준태의 GitHub Pages 홈페이지입니다.

공개 주소는 [https://snjune6.github.io](https://snjune6.github.io) 입니다.

## 로컬에서 보기

의존성 설치는 필요 없습니다. `index.html`을 브라우저로 열면 됩니다.

## 바꾸는 방법

`main`에 바로 커밋하지 않습니다.

1. 이슈를 열고 바꿀 내용을 적습니다.
2. 이슈 번호가 드러나는 브랜치에서 작업합니다.
3. 풀 리퀘스트를 열고 `Closes #번호`로 이슈를 연결합니다.
4. 리뷰 의견을 반영하고, CI가 통과하면 머지합니다.

자세한 순서는 [CONTRIBUTING.md](CONTRIBUTING.md)에 있습니다.

## 저장소 구성

| 파일 | 역할 |
| --- | --- |
| `index.html` | 페이지 본문 |
| `styles.css` | 화면 스타일 |
| `.github/workflows/ci.yml` | 페이지 기본 조건 검사 |
| `.github/workflows/pages.yml` | GitHub Pages 배포 |

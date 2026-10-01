# eeleehnij.github.io

Jinhee Lee 의 개인 홈페이지. Jekyll + GitHub Pages.

## 구조

```
_pages/about.md           홈 (소개 · Education · Experience)
_pages/publications.html  논문 목록
_pages/projects.html      프로젝트 목록 (_portfolio 컬렉션을 연도순으로 렌더)
_pages/cv.md              /files/JinheeLee_CV.pdf 로 리다이렉트
_portfolio/*.html         프로젝트 상세 페이지
_layouts/                 default · single · project
_includes/                head · site-nav · footer · scripts · seo
assets/css/main.scss      사이트 전체 스타일 (외부 테마 의존 없음)
_data/navigation.yml      상단 메뉴
```

## 로컬 실행

```bash
bundle exec jekyll serve
# 또는
jekyll serve
```

## 콘텐츠 추가

**프로젝트** — `_portfolio/` 에 html 파일을 추가하고 front matter 를 채운다.

```yaml
---
title: "제목"
excerpt: "목록에 보일 한 줄 설명"
collection: portfolio
type: research        # research | project | capstone — 태그 색이 결정됨
info: "학회/소속"      # 선택
year: 2025            # 목록 정렬 기준
thumbnails: /images/<폴더>/teaser.png   # 2개를 배열로 주면 나란히 표시
---
```

**논문** — `_pages/publications.html` 의 `.item` 블록을 복사해 채운다.

## 디자인

`assets/css/main.scss` 상단 `:root` 의 커스텀 속성(색·폰트·간격)만 바꾸면
사이트 전체 톤이 바뀐다. 다크 모드는 `prefers-color-scheme` 를 따르고,
상단 토글로 수동 전환하면 `localStorage` 에 저장된다.

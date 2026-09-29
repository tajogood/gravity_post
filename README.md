# 중력 우편함

열 때마다 Google 뉴스(한국) 헤드라인을 불러와 행성으로 만들고, 기사 키워드가 편지가 되어 날아가는 우주 우편함.

빌드 없이 `index.html` 하나로 동작합니다.

## GitHub Pages로 올리기

1. 이 폴더 내용을 저장소 루트에 올립니다.
2. Settings → Pages → Branch를 `main` / `/ (root)`로 지정합니다.
3. `https://<아이디>.github.io/gravity-post/` 에서 열립니다.

## 참고

- Google 뉴스 RSS를 공개 CORS 프록시(allorigins, corsproxy.io, codetabs)를 거쳐 불러옵니다. 모두 실패하면 파일에 들어 있는 2026-09-29 뉴스를 보여줍니다.

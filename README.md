# 밀리언드림 홈페이지

정적 HTML/CSS/JS 사이트입니다. 루트의 `index.html`을 배포하면 홈·내 소개·이야기·연락하기가 열립니다. `story/`의 네 파일은 실행학교 블로그 키트 원본에서 가져왔으며, `admin.html`과 샘플 게시글 두 개는 유지합니다.

Threads 프로필은 실제 게시 계정으로 사용자가 재확인한 `@rgoline1`을 연결했습니다. 공개 연락처는 Threads로 한정했습니다. 블로그 경험담은 사용자가 게시를 보류했으므로 `posts.json`에 넣지 않았습니다. 원래 키트의 예시 글 두 편은 로컬 `story/posts.sample.json`에 보관하고, 공개 `posts.json`은 빈 배열로 둡니다.

로컬 확인: `python3 -m http.server 8765` 후 `http://localhost:8765` 접속.

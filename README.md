# 온나라 AI 서무 소개 페이지

[움직이는 소개 페이지 바로 보기](https://chlvlftjsrkq.github.io/onnara-ai-document-distributor/onnara-intro/onnara-intro.html)

온나라 AI 서무의 소개 페이지를 GitHub Pages로 제공합니다. 문서·이름·점수는 설명용 가상 예시입니다.

프로그램 소스와 설치 안내의 원본은 [GitLab 저장소](https://gitlab.aigov.go.kr/pilddong/onnara-ai-document-distributor)에 있습니다.

## 소개 페이지 갱신

GitLab 원본에서 소개 HTML을 수정한 뒤 다음 명령을 실행합니다.

```powershell
node scripts/build-intro-site.mjs
```

생성된 `dist/onnara-intro-web/`의 파일을 이 저장소의 `main`에 반영하면 GitHub Pages가 갱신됩니다.
게시 원본은 `main` 브랜치의 루트(`/`)이며, `.nojekyll`을 포함합니다.

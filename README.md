# 온나라 AI 서무 소개 페이지

[제품 소개 · 흐름 체험 바로 보기](https://chlvlftjsrkq.github.io/onnara-ai-document-distributor/onnara-intro/onnara-intro.html)

**국가기관이든 지방자치단체든, 모든 서무 업무는 문서배부로부터.**

문서를 이해하고, 근거를 연결하고, 다음 업무를 제시합니다.

온나라 AI 서무 v1.8.0의 제품 소개와 다섯 단계 업무 흐름을 GitHub Pages로 제공합니다. 문서·이름·규정·답변은 설명용 가상 예시입니다. 실제 온나라·AI에 연결하거나 접수·결재를 실행하지 않습니다.

프로그램 소스와 설치 안내의 원본은 [GitLab 저장소](https://gitlab.aigov.go.kr/pilddong/onnara-ai-document-distributor)에 있습니다.

이 공개 저장소에는 소개용 정적 HTML만 게시합니다. 프로그램 실행 소스, 행정 문서, 실제 계정·키는 포함하지 않습니다. HTML은 단일 파일로 오프라인 열람이 가능하며 외부 폰트·CDN·추적 스크립트를 불러오지 않습니다.

## 소개 페이지 갱신

GitLab 원본에서 소개 HTML을 수정한 뒤 다음 명령을 실행합니다.

```powershell
node scripts/build-intro-site.mjs
```

생성된 `dist/onnara-intro-web/`의 파일을 이 저장소의 `main`에 반영하면 GitHub Pages가 갱신됩니다.
게시 원본은 `main` 브랜치의 루트(`/`)이며, `.nojekyll`을 포함합니다.

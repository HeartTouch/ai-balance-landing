# AI 소모임(밸런스형) — 인앱 브라우저 호환 경량 랜딩페이지

이 저장소는 인앱 브라우저에서도 멈춤 없이 열리도록 만든 초경량 랜딩페이지입니다.
메인 CTA 및 외부 열기 대상 링크: `https://m.site.naver.com/1OsuE`

## 배포(깃허브 페이지)
1. GitHub에 새 저장소를 만듭니다. 예: `ai-balance-landing`
2. 이 폴더의 파일들을 업로드합니다: `index.html`, `404.html`, `.nojekyll`, `README.md`
3. **Settings → Pages**로 이동하여
   - Source: `Deploy from a branch`
   - Branch: `main` (또는 default), Folder: `/ (root)` → **Save**
4. 잠시 후 접속: `https://<username>.github.io/<repo-name>/`

## 로컬 테스트
- 파일을 더블클릭해서 브라우저로 열면 됩니다.
- 인앱 감지 배너는 카카오/인스타/NAVER 웹뷰 등에서만 표시됩니다.

## 커스터마이징
- 링크 변경: `index.html`의 `naver_link` 위치(https://m.site.naver.com/1OsuE)를 원하는 URL로 바꾸세요.
- 색상/문구/이미지도 `index.html` 상단 스타일/히어로 영역에서 바로 수정 가능합니다.

## 참고
- `404.html`은 GitHub Pages 경로 문제 시 루트로 안전 리다이렉션을 제공합니다.
- `.nojekyll`은 GitHub Pages가 추가 빌드 없이 정적 파일로 서빙하도록 합니다.

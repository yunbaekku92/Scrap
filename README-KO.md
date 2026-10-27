# Telegram Scrap Automation — GitHub Pages 배포 안내

1. `YOUR_SUPPORT_EMAIL`을 본인이 관리하는 지원 이메일로 변경하세요. 파일 3개(index.html, privacy.html, terms.html)에 등장합니다.
2. GitHub 무료 계정에서 **Public** 저장소를 생성하고, 이름을 정확하게 `GITHUB_USERNAME.github.io`로 지정합니다. 여기서 GITHUB_USERNAME은 실제 본인의 GitHub 사용자 이름입니다(대소문자는 소문자로).
3. 이 압축파일에서 4개 파일(`index.html`, `privacy.html`, `terms.html`, `logo.png`)을 저장소 최상위에 업로드합니다. README-KO.md는 선택적으로 업로드합니다.
4. 저장소 Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → Folder: /(root) → Save.
5. 접속 주소: `https://GITHUB_USERNAME.github.io/` / `https://GITHUB_USERNAME.github.io/privacy.html` / `https://GITHUB_USERNAME.github.io/terms.html`.
6. Google Auth Platform → Branding → App domain의 세 URL 칸에 위 주소를 입력합니다. 앱 도메인 인증이 요구되면 Search Console에서 해당 사이트의 URL 접두사 소유권을 확인할 수 있습니다. Google OAuth 게시/인증 통과 여부는 보장되지 않습니다.

경고: GitHub Pages 사이트와 Public 저장소는 외부 공개됩니다. OAuth 토큰, 클라이언트 비밀번호, 스크랩 데이터 등은 업로드하지 마세요.

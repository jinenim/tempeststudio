# 템페스트스튜디오 회사 웹사이트

Google Play Console 조직 계정 전환(웹사이트 확인)과 앱의 개인정보처리방침 URL에 쓰는 정적 사이트입니다.
GitHub Pages가 `main` 브랜치의 저장소 루트를 그대로 배포합니다(빌드 없음).

| 파일 | 내용 |
| --- | --- |
| `index.html` | 회사 소개(한국어, 기본) |
| `privacy.html` | 개인정보처리방침(한국어, 정본) |
| `en/index.html`, `en/privacy.html` | 영어판 |
| `style.css` | 공용 스타일(밝은 하늘색 바탕, 다이스 폴리 일러스트 색을 포인트로) |
| `images/` | 다이스 폴리 세로 타이틀 화면(`dicepoly-title.webp`, 도시 그림 위에 로고를 합친 것), 로고 단독(`dicepoly-logo.webp`), 링크 공유 미리보기(`og.jpg`), 파비콘 |
| `.nojekyll` | GitHub Pages가 Jekyll 변환 없이 파일을 그대로 올리게 하는 표시 |
| `CNAME` | (도메인 연결 후 추가) 사용자 도메인 이름 |

- 문의 이메일은 모든 html에 같은 값이 들어 있습니다. 바꿀 때 전부 같이 바꿉니다.
- 게임이 모으는 정보가 바뀌면(광고 SDK, 본인인증 업체 등) 개인정보처리방침 두 개를 같이 고치고 시행일을 올립니다.
- `og:image`·`og:url`은 지금 GitHub Pages 주소(절대 주소)입니다. 도메인을 연결하면 바꿉니다.

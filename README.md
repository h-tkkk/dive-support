# kaltoelabs.com

칼퇴랩스 공식 사이트. GitHub Pages + 커스텀 도메인 `kaltoelabs.com`.

## 구조

| 경로 | 설명 |
|------|------|
| `/` | 회사 홈 |
| `/contact.html` | 문의 |
| `/dive/` | 다이브 소개·개인정보·지원·약관 |
| `/tempo/` | TEMPO 소개·개인정보·지원·약관 |
| `/hotfix/` | 핫픽스 소개·개인정보·지원·약관 |
| `/privacy.html` 등 | 예전 URL → 다이브/TEMPO로 리다이렉트 |

## 스토어에 넣을 URL

- 다이브 개인정보: `https://kaltoelabs.com/dive/privacy.html`
- 다이브 지원: `https://kaltoelabs.com/dive/support.html`
- TEMPO 개인정보: `https://kaltoelabs.com/tempo/privacy.html`
- 핫픽스 개인정보: `https://kaltoelabs.com/hotfix/privacy.html`
- 공통 문의: `kaltoelabs@gmail.com`

## 배포

```bash
git add -A
git commit -m "Refresh Kaltoe Labs company site"
git push origin main
```

Pages가 이 저장소 `main` 루트를 바라보면 수 분 안에 https://kaltoelabs.com/ 에 반영됩니다.

# Harim Moving Namecard

Harim Oh의 무빙 명함 웹페이지.

## 구성
- `index.html` — 명함 (스크롤하면 정보가 코너로 펼쳐지고 중앙에 카피 표시)
- `admin.html` — 중앙 텍스트 편집기. GitHub에 직접 커밋 → Vercel 자동 배포
- `data.json` — 중앙에 표시될 텍스트
- `*.svg` — 코너 4요소 (이름/인스타/이메일/전화)
- `AndaleMono.ttf` — 본문 폰트

## 어드민 사용
1. `/admin.html` 접속
2. GitHub fine-grained token 입력 (Contents: Read & write 권한)
3. 텍스트 입력 → PUBLISH → ~10초 후 본 페이지 갱신

## 모바일
세로일 때 가로로 돌려달라는 안내 표시. 가로 회전하면 데스크톱과 동일.

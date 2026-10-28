# LSSC 콘텐츠본부(콘텐츠 2본부 + 바이럴마케팅팀) 팀빌딩 채용 페이지

`index.html` 한 장으로 만든 정적 페이지입니다. 빌드 과정 없이 GitHub에 올리면 Vercel이 자동으로 배포합니다.

## 구성
- 인트로(3·2·1 카운트다운) → Hero("멈춰. 3초면 충분해.") → 릴스 광고 영상 → 숫자 → 팀별 소개 + 오픈 포지션 → About LSSC → 마무리 문구
- 지원 버튼은 나인하이어 공고로 새 탭 연결
  - 콘텐츠 2본부: mlulo1KH, uCvEqroj, Y2jwEnSx
  - 바이럴마케팅팀 바이럴 콘텐츠 마케터: X2xIfhAJ

## 릴스 영상 넣는 법
1. 세로형(9:16) mp4 파일을 `assets/videos/` 폴더에 넣습니다.
2. `index.html`에서 `<figure class="reel" data-video="">`의 따옴표 안에 경로를 적습니다. 예: `data-video="assets/videos/racelturn.mp4"`
3. 커밋·푸시하면 자동 재배포됩니다.

## 링크 미리보기 이미지
`assets/og-image.jpg` (원본: `assets/og-source.html`)

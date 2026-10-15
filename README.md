# 프랑스어 발음 카드 아카이브

공개 사이트: https://hyeon-seo-lab.github.io/french-pronunciation-cards/

`index.html`은 날짜별 카드 목록이고, 날짜별 발음 카드는 `cards/YYYY-MM-DD.html`에 저장합니다. 예를 들어 2026년 10월 15일 카드는 `cards/2026-10-15.html`입니다. 새 카드가 추가되어도 기존 날짜 카드는 그대로 보관됩니다.

## 매일 카드 추가

1. 그날의 프랑스어 표현으로 발음 카드 HTML을 만듭니다.
2. `cards/YYYY-MM-DD.html`에 새 날짜 파일을 추가합니다.
3. `index.html` 날짜 목록 맨 위에 링크를 추가하고 지난 링크는 모두 보존합니다.
4. 변경을 커밋하면 GitHub Actions가 GitHub Pages를 자동으로 배포합니다.

공개 저장소에는 프랑스어 학습 카드만 올립니다. Obsidian 개인 노트나 개인정보는 절대 넣지 않습니다. 발음은 방문자 브라우저의 프랑스어 음성합성(Web Speech API)을 사용합니다.

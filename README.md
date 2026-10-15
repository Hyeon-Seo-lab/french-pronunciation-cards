# 프랑스어 발음 카드 (GitHub Pages)

이 폴더만 GitHub 저장소에 올리면 발음 카드 웹페이지로 배포할 수 있습니다. Obsidian 보관함의 다른 노트는 이 폴더에 넣지 마세요.

## GitHub에 올리고 배포하기

1. GitHub에서 새 저장소를 만들고 이름을 `french-pronunciation-cards`로 지정합니다.
2. 저장소를 `Public`으로 설정합니다. GitHub Free 계정에서는 Pages 배포에 공개 저장소가 필요합니다.
3. 이 폴더의 파일과 `.github` 폴더를 저장소 최상위에 업로드합니다. GitHub 웹에서 **Add file → Upload files**로 올려도 됩니다.
4. `Settings → Pages`에서 **Build and deployment → Source**를 `GitHub Actions`로 설정합니다.
5. `Actions` 탭에서 `Deploy pronunciation cards` 실행이 성공하면 페이지 주소는 `https://<GitHub아이디>.github.io/french-pronunciation-cards/`입니다.

이 저장소의 Pages 사이트는 누구나 볼 수 있습니다. 파일에는 학습 문장만 포함되며, 개인 노트는 넣지 마세요. 발음은 방문자 브라우저의 프랑스어 음성합성 기능을 이용합니다.

## 문장 갱신

새 날짜의 발음카드 내용을 `index.html`에 반영해 저장소에 다시 올리면 Pages가 자동으로 재배포합니다.

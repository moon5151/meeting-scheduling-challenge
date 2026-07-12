# AutoSlot 웹 프로토타입

## 실행 흐름
index → Scene 0 → Scene 1 → Scene 1.5 → Scene 2 → Scene 3 → Scene 4 → Scene 5

마지막 화면의 `회의 현황 보기` 버튼을 누르면 시작 화면으로 돌아갑니다.

## 누구나 볼 수 있는 URL로 배포하기

### Netlify Drop
1. 이 ZIP 파일의 압축을 풉니다.
2. Netlify Drop 페이지에 압축을 푼 폴더 전체를 드래그합니다.
3. 생성된 URL을 복사해 공유합니다.

`index.html`이 폴더 최상위에 있어야 합니다.

### GitHub Pages
1. 새 GitHub 저장소를 만듭니다.
2. 압축을 푼 파일 전체를 저장소 루트에 업로드합니다.
3. Settings → Pages → Deploy from a branch를 선택합니다.
4. main 브랜치와 /(root)를 선택해 저장합니다.

# AR Photocard (1·2 버전)

NFT Marker Creator에서 Filename을 `1`, `2`로 설정해서 만든 마커 파일을 사용하는 버전입니다.

## 폴더 구성
- `assets/1-image.png`, `assets/2-image.png` : 인쇄용 이미지(참고용)
- `assets/1-video.mp4`, `assets/2-video.mp4` : 각 카드 위에 뜰 영상
- `markers/` : 아래 마커 파일 6개를 넣으세요.
  - 1.iset / 1.fset / 1.fset3
  - 2.iset / 2.fset / 2.fset3

## 배포
이 폴더를 Netlify에 그대로 올리면 끝입니다.

## 동작
- 1번 카드 → 1번 영상, 2번 카드 → 2번 영상
- iOS 자동재생 정책으로 기본은 음소거 상태
- 하단 버튼으로 소리 On/Off 제어 가능

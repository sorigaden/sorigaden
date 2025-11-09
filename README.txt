
# WE 패키지 (AR 2개 + NFC 1개)
1) 이 폴더 전체를 Netlify에 업로드하세요.
2) /we/config.js 파일에 Firebase Storage '다운로드 URL(https)'을 붙여넣으면 바로 작동합니다.
   - AR1_VIDEO_URL, AR2_VIDEO_URL, NFC1_VIDEO_URL
   - (선택) AR1_MARKER_PNG_URL, AR2_MARKER_PNG_URL은 미리보기 용도
3) 경로
   - /           (기본 홈)
   - /we/        (콘서트 홈)
   - /we/ar/1/   (AR 1, 자동재생 무음)
   - /we/ar/2/   (AR 2, 자동재생 무음)
   - /we/nfc/1/  (NFC 1, 사운드/컨트롤)
   - /we/ar/mindar/ (마커 인식 AR, 2개 타깃) → targets.mind 파일을 같은 폴더에 업로드 필요
4) MindAR targets.mind 만들기: PNG 2장을 MindAR Image Compiler로 묶어 생성 후 /we/ar/mindar/ 에 업로드.
5) Firebase 주소는 반드시 https://firebasestorage.googleapis.com/... (token 포함) 이어야 합니다. gs:// 경로는 안 됩니다.

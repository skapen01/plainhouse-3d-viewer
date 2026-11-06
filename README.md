# 3D 모델 뷰어

STP·STEP·STL·IGES 파일을 브라우저에서 열어 치수 확인, 측정, 간단한 편집 후 STL로 저장하는 사내용 도구입니다.
모델 파일은 각자의 브라우저 안에서만 처리되며 서버로 전송되지 않습니다.

- `index.html` — 뷰어 본체
- `occt-import-js.js`, `occt-import-js.wasm` — STEP·IGES 해석 엔진 (Open CASCADE, LGPL)
- `lib/` — three.js 0.147.0 (MIT)
- `netlify.toml` — 배포 설정 (빌드 없음)

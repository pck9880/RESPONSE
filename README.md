# RESPONSE — THE WORLD IS SILENT

고립된 지하철 객차 한 량을 중심으로 한 무료 웹 생존/생활형 게임 프로토타입.

**게임:** https://pck9880.github.io/RESPONSE/

## 현재 구현 (Phase 004)
- 기본 페이지 `index.html`: 12×5 객차의 360° 자유 회전, 드래그 방향 수정, 70–380% 확대·축소, 가까운 벽 숨김, 간단한 30초 자동 생활 시연.
- HTML5 Canvas 다각형 3D 투영 + 기본 시점 픽셀 PNG 혼합. **전체 방향이 같은 품질인 완성 3D 그래픽은 아님.**
- 기존 세 선택지(주변 살피기/휴대폰 확인/일어나기)와 `response_save_v1` 로컬 저장을 유지합니다.
- 11종 PNG 원본 `assets/pixel/`, 배치 데이터 `assets/layout.json` 보존.
- **이전 Phaser 버전 백업:** `classic-phaser.html` (단독 실행 가능).
- 40분/게임 1일 시계 및 탭 비활성화 중 일시정지는 기본 구현. 생존 수치·사망 및 영구 도감은 기획 단계입니다.

## 이어서 개발하기
- **`docs/DEVELOPMENT_STATE.md`를 먼저 읽으세요.** 확정 설정, 구현 완료, 미구현, 다음 작업이 있습니다.
- `main` 커밋마다 `.github/workflows/pages.yml`로 GitHub Pages 자동 배포.
- 기존 데이터 삭제/초기화 없이 단계적으로 개발합니다.
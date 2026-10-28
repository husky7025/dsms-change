# 결보강 시간표 자동 탐색 (대전동산중학교)

대전동산중학교 결보강(수업 교체·보강) 탐색 웹앱의 GitHub Pages용 정적 버전입니다.  
서버 없이 `index.html` 하나만으로 브라우저에서 안전하게 동작하며, **구글 스프레드시트 실시간 연동**을 지원합니다.

## 파일 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 앱 본체 (UI + 시간표 내장 + 탐색 결과 + HWPX 생성 + 계획서 인쇄) |
| `engine.js` | 탐색 엔진 (시간표 파싱·교체/보강 탐색·공동공강·연속수업 제한·시뮬레이션) |
| `timetable.csv` | 동산중 정규 시간표 데이터 (UTF-8 BOM) |

## GitHub Pages 배포 방법

1. 이 폴더의 파일들을 GitHub 새 저장소에 push
2. 저장소 Settings → Pages → Deploy from a branch → `main` / `/(root)` 선택 후 Save
3. 1~2분 후 `https://<사용자명>.github.io/<저장소명>/` 으로 접속

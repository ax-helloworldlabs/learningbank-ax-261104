# AX 레시피 업무 프로세스 개선 (러닝뱅크)

현장의 반복 업무를 진단하고 Claude로 자동화 흐름을 만들어 운영·확산안까지 완성하는 2일(16시간) 실습 과정의 수강생 안내 페이지입니다. 15개 과정 중 14번 과정.

- 일정: 2026년 11월 4일(수)–5일(목) 09:00–18:00 (점심 12:00–13:00)
- 장소: 서울 송파구 법원로 114, 문정엠스테이트 A동 1006~1007호 회의실 (러닝뱅크 방문 교육)
- 실습 도구: Claude Cowork — **Claude 계정 지원 없음** (수강생이 직접 준비)

## 배포 방법 (GitHub Pages)

1. `ax-helloworldlabs` 조직에 `learningbank-ax-261104` 저장소를 만듭니다. → `https://ax-helloworldlabs.github.io/learningbank-ax-261104/`
2. 이 폴더의 파일을 모두 저장소 최상위에 올립니다(`.nojekyll` 포함).
3. **Settings → Pages**에서 `Deploy from a branch`, `main` / `/(root)` 저장.

## 무엇을 어디서 고치나

| 고칠 내용 | 파일 · 위치 |
|---|---|
| 날짜·시간·장소 요약 띠 | `index.html` `.event-strip` |
| 준비물 카드(신분증 / 노트북·충전기 / Claude 계정) | `index.html` `#preparation` `.prep-card` |
| 일정 카드·장소·지도 링크 | `index.html` `#place` |
| 주소 복사 버튼의 주소 | `script.js` 첫 줄 `const address` |
| 2일 커리큘럼(DAY 1: 모듈 1–4, DAY 2: 모듈 5–7) | `index.html` `#curriculum` `.day-label`, `<details class="module">` |
| Claude 계정 미지원 안내 띠 | `index.html` `#support` |
| 이 페이지 전용 스타일(2일 표시, DAY 라벨) | `index.html` `<head>` 안 `<style>` |

## 확인할 정보

- **문의 전화**: 지난 페이지와 같은 070-8833-7771을 썼습니다. 엑셀의 14번 과정 연락처는 070-8833-7780입니다.
- **2일차 시간 배분**: 엑셀 편성(흐름 구현 4H)을 지키느라 모듈 5가 09:00–12:00 + 13:00–14:00로 점심을 걸칩니다.
- **공통 정보 재사용**: 신분증 안내, 사전 안내 PDF, SafariON 계정, 카카오 채널은 seintogether-ax-261104 페이지 값을 그대로 썼습니다.
- **강사명**: 엑셀에는 김용승 강사로 되어 있으나 지난 페이지들처럼 표기하지 않았습니다.

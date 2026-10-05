# 쇼츠 차단 글 보완안 — 2026-10-05

## 상태

한·영 교체 원고는 검토용 초안이다. `docs/` 아래에 있어 Hugo 공개 페이지를 생성하지 않는다. 현재 공개 쇼츠 글은 내부 링크만 수정했다. 승인 후 기존 `content/{ko,en}/post/2026-03-29-how-to-block-youtube-shorts.md`의 원고로 교체할 때 `draft: false`로 변경해야 한다. 기존 slug·translationKey를 유지한다. lastmod는 실제 게시 시각으로 갱신한다.

## 주요 변경

- ‘완벽 차단’, ‘도파민 수치 훼손’, ‘뇌 변형’, ‘작업 기억 파괴’, ‘최소 1~2시간 확보’ 단정을 제거한다.
- PC 웹·Android Firefox 웹·모바일 앱의 범위를 구분한다.
- Unhook 옵션명을 배포 설명에 맞추고 UI 숨김과 URL 접근 차단을 구분한다.
- 공식 모바일 쇼츠 피드 제한과 0분 설정을 추가하되, 개인 계정의 알림은 무시할 수 있음을 명시한다.
- Chrome의 원래 uBlock Origin 지원 종료를 반영한다. Lite 기능은 미검증이므로 동일 절차를 안내하지 않는다.
- 기존 CSS 필터의 광범위한 행 선택과 코스메틱 필터/네트워크 필터 혼동을 설명한다. 미검증 대체 코드는 제공하지 않는다.
- 경험·효과를 실제 테스트한 것처럼 쓰지 않는다.

## 확인한 근거

- https://support.google.com/youtube/answer/16671528?hl=en — 쇼츠 피드 제한, 0분, 알림 무시 가능.
- https://support.google.com/youtube/answer/6342839?hl=en — 쇼츠 적게 보기, 홈 추천과 시청 기록 관리.
- https://chromewebstore.google.com/detail/unhook-remove-youtube-rec/khncfooichmfjbepaaaebmommgaepoid — Chrome 옵션 목록.
- https://addons.mozilla.org/en-US/firefox/addon/youtube-recommended-videos/ — Firefox 옵션 목록과 Android 모바일 웹 지원.
- https://github.com/gorhill/uBlock — 브라우저 지원 환경.
- https://developer.chrome.com/docs/extensions/develop/migrate/mv2-deprecation-timeline — Chrome Manifest V2 종료.

Edge 배포 링크는 공식 Firefox 개발자 목록에 연결된 주소를 사용했다. Edge에서의 실제 설치·옵션은 시험하지 않았다. 한국어 도움말 링크의 번역 문구는 직접 검증하지 않았으므로 영문 메뉴 이름을 함께 표기했다.

## 게시 전 남은 확인

1. PC Chrome·Edge·Firefox에서 설치 버전과 옵션 화면을 기록하고 홈/검색/구독/일반 영상/쇼츠 직접 링크 동작을 확인한다.
2. Android Firefox 모바일 웹, Android·iPhone 앱에서 메뉴 표시와 제한 무시 동작을 확인한다.
3. 공개 원고 교체 후 한·영 제목·설명·본문 링크·모바일 표 표시를 확인한다.

## 내부 링크 수정

| 기존 대상 | 수정 대상 | 위치 수 |
|---|---|---:|
| `/ko/stone-age-brain-vs-gpt/` | `/ko/post/stone-age-brain-vs-gpt/` | 2 |
| `/ko/it-productivity-local-ai-guide/` | `/ko/post/it-productivity-local-ai-guide/` | 1 |
| `/it-productivity-local-ai-guide/` | `/post/it-productivity-local-ai-guide/` | 1 |
| `/post/2026-03-29-how-to-block-youtube-shorts/` | `/ko/post/how-to-block-youtube-shorts/` | 1 |
| `/about/`（한국어 개인정보처리방침） | `/ko/about/` | 1 |

앞의 네 항목이 기존 감사의 깨진 링크 4종이며 중복 포함 5곳이다. 마지막 항목은 404가 아니라 언어 연결 오류다.

---
title: "유튜브 쇼츠 차단 방법: PC 피드 숨기기와 모바일 시청 제한"
date: 2026-03-29T16:00:00+09:00
lastmod: 2026-10-05T13:00:00+09:00
draft: true
categories: ["Productivity"]
series: ["Productivity-Hacks"]
tags: ["디지털디톡스", "유튜브쇼츠차단", "IT생산성"]
author: "Tikklabs Editor"
slug: "how-to-block-youtube-shorts"
translationKey: "youtube-shorts-guide"
cover:
  image: "/images/focus_thumbnail.png"
  alt: "노트북 화면에 집중하는 모습을 표현한 일러스트"
description: "PC에서 Unhook으로 유튜브 쇼츠와 추천 피드를 숨기고, 모바일 앱에서 쇼츠 시청 제한을 설정하는 방법과 각 기능의 한계를 설명합니다."
---

유튜브를 자료 검색에 쓰려다가 쇼츠와 추천 영상을 계속 보게 된다면, 접속할 때 보이는 화면부터 바꿔볼 수 있습니다. 먼저 **추천 노출 줄이기, 화면 숨기기, 시청 시간 제한**을 구분해야 합니다. 같은 ‘차단’이라는 표현을 쓰더라도 적용 범위와 효과는 다릅니다.

이 글은 2026년 10월 5일 공식 도움말과 개발자 배포 페이지를 확인해 작성한 보완 초안입니다. 실제 기기에서 설치·작동을 시험한 리뷰는 아닙니다.

## 사용 환경에 맞는 방법 선택하기

| 환경 | 방법 | 적용 범위와 한계 |
|---|---|---|
| PC Chrome·Edge·Firefox | Unhook | 해당 브라우저의 유튜브 웹 화면 숨기기. 앱이나 다른 브라우저까지 적용되는 것은 아닙니다. |
| Android Firefox | Unhook | 개발자가 모바일 웹 지원을 안내합니다. 유튜브 앱에는 적용되지 않습니다. |
| Android·iPhone 유튜브 앱 | 쇼츠 피드 제한 | 0분 설정도 가능하지만 개인 계정의 제한 알림은 무시할 수 있습니다. |
| 유튜브 앱 홈 | 쇼츠 적게 보기 | 추천을 줄이는 기능입니다. 쇼츠 전체 접근 차단과 다릅니다. |
| PC·모바일 계정 설정 | 시청 기록 삭제 및 사용 중지 | 홈 추천을 없애는 방법으로 공식 안내됩니다. 기존 시청 기록 삭제에 주의해야 합니다. |

## PC: Unhook으로 홈 추천과 쇼츠 숨기기

Unhook은 유튜브 화면의 추천 영역을 숨기는 확장 프로그램입니다. 개발자 공식 배포 페이지에서 설치하고, 이름이 비슷한 다른 확장 프로그램과 혼동하지 마세요.

- [Chrome 배포 페이지](https://chromewebstore.google.com/detail/unhook-remove-youtube-rec/khncfooichmfjbepaaaebmommgaepoid)
- [Firefox 배포 페이지](https://addons.mozilla.org/en-US/firefox/addon/youtube-recommended-videos/)
- [Edge 배포 페이지](https://microsoftedge.microsoft.com/addons/detail/unhook-remove-youtube-r/hebpjnnclppdnfghdnmhgdljmjpfhggk)

1. 사용하는 브라우저에 설치하고 유튜브 페이지를 새로고침합니다.
2. 확장 프로그램 아이콘을 열어 **Hide Homepage Feed**를 켭니다.
3. 쇼츠 관련 숨김 옵션을 켭니다. Chrome 배포 설명에는 **Hide YouTube Shorts**, Firefox에는 **Hide Shorts Tab**으로 안내되어 있어 버전별 표현이 다를 수 있습니다.
4. 필요하면 관련 영상 숨김과 자동재생 중지도 설정합니다.
5. 홈·검색·일반 영상·쇼츠 직접 링크를 각각 열어 남아 있는 영역과 정상 재생 여부를 확인합니다.

화면 요소를 숨기는 기능을 모든 쇼츠 URL의 접근 차단으로 해석하면 안 됩니다. 유튜브 화면 구조가 바뀌면 효과가 달라질 수 있습니다. 이상이 생기면 숨김 옵션을 하나씩 끄거나 확장 프로그램을 비활성화하고 새로고침하세요.

## 모바일 앱: 쇼츠 피드 제한 설정하기

유튜브 공식 도움말은 다음 경로를 안내합니다.

1. 로그인한 유튜브 앱에서 **내 페이지(You) → 설정**으로 들어갑니다.
2. **시간 관리(Time management) → 쇼츠 피드 제한(Shorts feed limit)**을 엽니다.
3. 원하는 시간을 선택합니다. 도움말에는 **0분** 선택도 포함되어 있습니다.

제한에 도달하면 알림이 나타나며, 개인 계정에서는 이를 닫거나 무시할 수 있습니다. 이 기능을 해제할 수 없는 잠금장치로 소개해서는 안 됩니다. 메뉴가 보이지 않으면 앱 업데이트와 계정 상태를 확인하고, 공식 도움말의 현재 안내와 비교하세요. 이 설정이 PC 웹에도 같은 방식으로 적용된다고 가정하지 마세요.

[공식 출처: 쇼츠 피드 제한 설정](https://support.google.com/youtube/answer/16671528?hl=ko)

## 확장 프로그램 없이 추천 줄이기

앱 홈의 쇼츠 묶음 상단 메뉴에서 **쇼츠 적게 보기(Show fewer Shorts)**를 선택할 수 있습니다. 이는 노출을 줄이려는 피드백이며, 쇼츠 탭이나 직접 링크를 없애는 기능은 아닙니다.

홈 추천 자체를 없애고 싶다면 공식 도움말에 안내된 **시청 기록 삭제 및 사용 중지**를 검토할 수 있습니다. 기록을 삭제하면 이전 시청 목록을 잃게 되므로, 화면을 숨기는 방법보다 먼저 선택해야 할 이유가 있는지 판단하세요. 쇼츠만 골라 차단하는 설정도 아닙니다.

[공식 출처: 추천 및 검색결과 관리](https://support.google.com/youtube/answer/6342839?hl=ko)

## uBlock Origin 필터를 사용할 때 확인할 점

기존 글의 필터는 화면 요소를 숨기는 코스메틱 필터입니다. 네트워크 차단 규칙이 아니며, 홈 추천 전체 제거도 입증되지 않았습니다. 특히 첫 규칙의 `ytd-rich-grid-row`는 쇼츠 여부와 무관하게 해당 행을 선택할 수 있어 일반 영상까지 숨길 위험이 있습니다.

현재 Chrome에서는 원래 uBlock Origin이 사용하는 Manifest V2를 지원하지 않습니다. Firefox용 uBlock Origin과 uBlock Origin Lite를 같은 제품·설정 화면으로 안내해서도 안 됩니다. 개발자 문서를 확인하고 사용하는 제품의 기능을 구분하세요.

이 초안에서는 작동을 검증하지 않은 대체 필터를 제공하지 않습니다. 필터가 필요한 독자는 사용하는 브라우저와 확장 버전에서 홈·검색·구독·일반 영상·쇼츠 화면을 각각 시험한 뒤 적용해야 합니다.

[개발자 출처: uBlock Origin 지원 환경](https://github.com/gorhill/uBlock)
[Chrome 공식 출처: Manifest V2 지원 종료](https://developer.chrome.com/docs/extensions/develop/migrate/mv2-deprecation-timeline)

## 효과는 자신의 이용 기록으로 판단하기

이 설정으로 누구나 일정 시간을 되찾는다고 약속할 수는 없습니다. 설정 전후 며칠간 유튜브 이용 시간과 작업 중 접속 횟수를 비교해 자신에게 도움이 되는지 판단하세요.

이 글은 도파민 수치나 뇌 변화에 대한 의학적 설명을 근거로 차단을 권하지 않습니다. 목적은 필요한 영상을 검색하고 시청하기 쉬운 환경을 만드는 것입니다.

[관련 글: 석기시대 뇌 vs GPT](/ko/post/stone-age-brain-vs-gpt/)

# OOC ARCADE

롤플레이용 OOC 테스트·페어틀·도구를 한곳에 모아 분류별로 골라 볼 수 있는 링크 모음 페이지 — 단일 HTML 파일.

**https://yuuuulll35.github.io/ooc-arcade/**

## 구성

| 영역 | 내용 |
|---|---|
| 헤더 | 제목, 계정 핸들 |
| 공지사항 | 안내 문구 3줄, X · 포스타입 링크 |
| 필터 | 전체 / OOC / 페어틀 / 도구함 |
| 카드 | 이모지, 분류(OOC는 수록 개수 포함), 제목, 한 줄 설명. 누르면 각 작품 페이지가 새 탭에서 열림 |

## 작품 추가

`index.html` 아래쪽 `items` 배열에 한 줄을 더한다.

```js
{t:"제목", g:"이모지", d:"한 줄 설명", c:"ooc", n:3, url:"https://..."},
```

- `c`: `ooc` · `pair` · `tool` 중 하나
- `n`: 수록된 OOC 개수. 없으면 생략

## 폰트

모든 폰트는 SIL Open Font License 1.1을 따르며, 저장소에 포함되지 않고 Google Fonts에서 불러옵니다.

| 폰트 | 쓰임 | 저작권 | 제공 |
|---|---|---|---|
| IBM Plex Sans KR | 본문 전체 | © IBM Corp. | Google Fonts |
| Fredoka | 제목 로고 | © The Fredoka Project Authors | Google Fonts |

이모지는 보는 기기의 시스템 이모지 글꼴로 표시됩니다.

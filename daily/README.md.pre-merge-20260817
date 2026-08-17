# Daily lesson archive contract

- `day-NN.html`: Gmail 본문과 동일한 standalone HTML 원본
- `manifest.json`: GitHub Pages 목록과 진행률이 읽는 메타데이터
- `index.html`: 브라우저용 일일 학습 아카이브

`manifest.json`의 `lessons` 항목은 다음 필드를 사용한다.

```json
{
  "day": 1,
  "week": 1,
  "dayInWeek": 1,
  "kind": "theory",
  "title": "오늘의 주제",
  "summary": "한 줄 요약",
  "path": "day-01.html",
  "publishedAt": "2026-07-30T09:00:00+09:00"
}
```

일일 자동화는 페이지 파일과 manifest를 먼저 커밋·푸시하고, 같은 HTML을
Gmail 본문으로 발송한다. 한쪽만 성공한 경우 다음 실행에서 기존 원본을
재사용해 복구하고 새 Day로 넘어가지 않는다.

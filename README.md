# 化學筆記 Chemistry Notes

個人化學學習筆記整理

## 目錄

- [普通化學](general-chemistry/)
  - [元素週期性質趨勢](general-chemistry/periodic-trends.md)
  - [元素週期性質測驗題庫](general-chemistry/periodic-trends-quiz.json) (30題)
  - [測驗答案與解析](general-chemistry/periodic-trends-answers.json)

## 題庫 JSON 格式說明 (v1.1)

題目檔 (`*-quiz.json`) 結構：
```json
{
  "id": 1,
  "question": "題目內容",
  "question_image": null,
  "options": { "A": "選項A", "B": "選項B", "C": "選項C", "D": "選項D" },
  "options_image": null
}
```

答案檔 (`*-answers.json`) 結構：
```json
{
  "id": 1,
  "answer": "C",
  "explanation": "解析說明",
  "explanation_image": null
}
```

### 圖片欄位說明

| 欄位 | 用途 | 範例情境 |
|------|------|----------|
| `question_image` | 題目圖片 | Lewis 結構、軌域圖、解剖圖 |
| `options_image` | 選項圖片 | 四個選項都是圖（分子結構比較） |
| `explanation_image` | 解析圖片 | 詳細軌域填充圖、反應機制圖 |

- 有值（相對路徑）= 顯示圖片
- `null` = 純文字

## 授權

個人學習用途

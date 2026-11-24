---
name: チャレンジ提出
about: ブラインド判定チャレンジの提出（第1部＋第2部の JSON）
title: "提出: anon-handle"
labels: submission
assignees: ''
---

以下の JSON を `task/submission-template.json` の形式で貼り付けてください。
（1ハンドル1提出・個人情報は記載しないでください）

```json
{
  "handle": "anon-your-handle",
  "disposition": "...",
  "applied_statutes": [],
  "cited_references": [],
  "cited_paragraphs": {},
  "reasons": {
    "disposition_reason": "...",
    "inventive_step_reason": "..."
  },
  "ai_draft_evaluation": {
    "disposition": "...",
    "applied_statutes": [],
    "cited_references": [],
    "targets": {
      "/disposition": "accept|reject",
      "/applied_statutes": "accept|reject",
      "/cited_references": "accept|reject",
      "/claim_chart": "accept|reject"
    },
    "reasons": "...",
    "corrections": ""
  }
}
```

# 資料約定

這些內容是本地合成演練資料，不代表真實人物、機構、作品或交易。原始值按來源記錄；空值和待核狀態表示尚未確認，不等同否定、零或已完成。

多语种艺术史原文、译文版本、读者任务和理解反馈。

- `passages.csv`：欄位 `passage_id, work_id, language, context, source_version, rights_state`。
- `translations.csv`：欄位 `translation_id, passage_id, target_language, version, term, rendering, editor_state`。
- `reader_tasks.csv`：欄位 `task_id, translation_id, audience, experience, assigned_on, task_version`。
- `responses.csv`：欄位 `response_id, task_id, responded_on, answer_code, confidence, review_state`。

同一標識只在其對應資料域內使用；版本、時間和狀態欄位保留各自來源含義。

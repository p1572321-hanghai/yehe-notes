# 对话记录

本文件夹保存 Muse 对话记录的全文转录，按聊天、按天分文件存放。

- `main/`：主对话
- `batch-x-twitter-tweet-generator/`：侧聊「Batch X/Twitter tweet generator」
- `open-google-in-cloud-browser/`：侧聊「Open Google in cloud browser」
- `generate-douyin-style-selfie-video/`：侧聊「Generate Douyin style selfie video」
- `remove-text-from-image-background/`：侧聊「Remove text from image background」

每个每日文件内按时间顺序记录当天的全部消息，格式为 `### HH:MM 用户` / `### HH:MM Muse`，消息正文原文保存，不做删减或改写。时间均为北京时间（Asia/Shanghai）。

`_state.json` 记录每个聊天的导出水位（已导出的最大 event_seq），供每日增量推送使用。

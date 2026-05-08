# Finn_CN-holidays_2026-2027

一个给 Google Calendar 订阅用的公开中国节假日 `.ics` 日历源。

## 订阅地址

启用 GitHub Pages 后，订阅地址形态为：

```text
https://<github-user>.github.io/Finn_CN-holidays_2026-2027/calendar.ics
```

在 Google Calendar 中使用：

1. 打开 Google Calendar。
2. 点击“其他日历”旁边的 `+`。
3. 选择“通过网址添加”。
4. 粘贴上面的 `.ics` URL。

## 内容范围

`calendar.ics` 当前包含：

- 2026 年中国法定休假安排。
- 2026 年调休上班日。
- 2026-2027 年追加节日：情人节、七夕节、重阳节。

2027 年国务院办公厅法定节假日安排尚未发布，因此本项目暂不预测 2027 年法定休假和调休。等官方通知发布后再更新。

## 命名规则

- `休｜节日名`：放假日期。
- `班｜节日名调休`：调休上班日期。
- `节｜节日名`：追加节日，不代表法定休假。

## 数据来源

- 2026 年法定休假与调休：[国务院办公厅关于 2026 年部分节假日安排的通知](https://www.gov.cn/gongbao/2025/issue_12406/202511/content_7048922.html)，中国政府网。
- 七夕节、重阳节对应公历日期：按农历日期换算后写入。
- 情人节：每年 2 月 14 日。

## GitHub Pages 发布

1. 创建公开 GitHub 仓库 `Finn_CN-holidays_2026-2027`。
2. 将本地仓库推送到 GitHub。
3. 在 GitHub 仓库设置中打开 Pages。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`。
6. 发布完成后使用 Pages URL 订阅 `calendar.ics`。

## 更新原则

- 只加入公开、可订阅、不会泄露私人信息的日历事件。
- 官方法定节假日以国务院办公厅通知为准。
- 2027 年官方通知发布前，不加入预测性法定休假或调休事件。

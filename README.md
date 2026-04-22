Description
This n8n workflow is a Gmail-to-Telegram automation designed to archive and notify you about incoming emails in real-time.

How it Works:
Monitor: Every 5 minutes, it checks your Gmail account for new messages using a custom Cron expression.
Archive: It automatically logs the details of each new email—specifically the Sender, Read/Unread status, Subject, Category, and a Snippet of the body—into a specific Google Sheet.
Notify: Immediately after the row is added to the spreadsheet, it sends a formatted summary of that email to a specific Telegram chat.
Technical Breakdown:
Trigger: Gmail Trigger (Polling mode).
Storage: Google Sheets (Append operation).
Output: Telegram (SendMessage operation).
Key Benefits:
1.** Centralized Logging**: Keeps a permanent, searchable record of all your emails in Google Sheets.
2. Instant Visibility: You get notified of important emails on Telegram without having to open your inbox.
3. Custom Filtering: By default, it captures the “Category” and “Labels” to help you distinguish between personal, social, or promotional emails at a glance.

Link to view : https://creators.n8n.io/workflows/15182

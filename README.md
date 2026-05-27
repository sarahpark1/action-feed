# action-feed

Personal dashboard that aggregates tagged activity from multiple platforms into a unified view.

## 🔧 Data Source
- Microsoft 365 SharePoint List
- Powered via Power Automate

## 🚀 Features
- Aggregated notifications (Figma, Teams, etc.)
- Status tracking (Inbox, Done, Snoozed)
- Real-time feed sync
- Search and filtering
- Links to tagged item

## 🔗 Setup

1. Open the action feed
2. Enter your SharePoint List API URL: https://.../_api/web/lists/getbytitle('Action Feed')/items
3. Click **Connect**
4. Click **Sync Feed**

## 🧠 Notes

- Uses browser session for authentication
- No data leaves Microsoft 365
- Requires active login to SharePoint

## ✏️ Updating the app

1. Edit `index.html`
2. Commit changes
3. GitHub Pages updates automatically

---

Built by Sarah Park

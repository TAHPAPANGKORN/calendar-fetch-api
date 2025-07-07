# 📅 Informatics Schedule Viewer

This project is a simple frontend web page that displays today's and tomorrow's events from a public Google Calendar.

---

## 🌐 Live Features

- Fetches events from a Google Calendar using the Google Calendar API.
- Displays data in a styled HTML table.
- Auto updates for today's and tomorrow's dates.
- Localized in Thai (`th-TH`).

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/FTGFLabs/calendar-fetch-api.git
cd calendar-fetch-api
```

### 2. Create `config.js` File

In the project root or next to your `index.html`, create a file named `config.js` with the following content:

```js
const apiKey = 'yourGoogleCalendarApiKey';
```

> 🛑 **Do not share your real API key in public repositories.**

### 3. Open `index.html` in a Browser

You can simply double-click `index.html` to open it in your browser.

Or, to serve it with a local server (recommended to avoid CORS issues with some APIs):

```bash
npx serve .
# or use any local server like http-server, live-server, etc.
```

---

## 📝 Notes

- The calendar used is: `pr@informatics.buu.ac.th`
- Make sure the calendar is publicly accessible, or the API will return empty results.
- The script uses Thai locale and Asia/Bangkok timezone formatting.

---

## 📁 File Structure

```
calendar-fetch-api/
├── index.html       # Main frontend HTML page
├── config.js        # Contains your API key (not included by default)
└── README.md        # Project documentation
```

---

## 📄 License

MIT License

---

## 👤 Maintained by

**FTGF Labs**  
[GitHub](https://github.com/FTGFLabs)

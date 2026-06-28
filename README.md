# 📋 Job Application Tracker

A clean, lightweight web app to help you track your job applications, monitor interview schedules, and manage your placement journey — all from a simple browser dashboard.

---

## 🚀 Features

- **Dashboard Analytics** — Live summary cards showing total applications, interviews scheduled, rejections, and offers at a glance
- **Add Applications** — Log a company name, job role, date, and status in seconds
- **Live Search** — Filter your applications instantly by company or role name
- **Status Updates** — Update the status of any application inline, directly from the table
- **Color-coded Badges** — Visual status indicators (Applied, Shortlisted, Interview Scheduled, Rejected, Selected)
- **Persistent Storage** — All data is saved to `localStorage`, so your records survive page refreshes

---

## 🛠️ Tech Stack

| Layer      | Technology             |
|------------|------------------------|
| Frontend   | HTML, CSS, JS  |
| Backend    | Node.js + Express      |
| Storage    | Browser `localStorage` |

---

## 📁 Project Structure

```
jobtracker/
├── index.html      # Frontend UI — dashboard, form, and application table
├── server.js       # Express server to serve the static frontend
└── package.json    # Project metadata and start script
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or above)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/shrravya10/jobtracker.git
cd jobtracker

# 2. Install dependencies
npm install

# 3. Start the server
npm start
```

Then open your browser and visit:

```
http://localhost:8080
```

---

## 📸 Usage

1. Fill in the **Company Name**, **Job Role**, **Application Date**, and **Status** in the form on the left.
2. Click **Track Application** to add it to your records.
3. Use the **search bar** to quickly filter applications.
4. Use the **dropdown** in the Update Status column to change an application's status at any time.
5. The **dashboard cards** at the top update automatically to reflect your current stats.

---

## 📊 Application Statuses

| Status               | Meaning                                 |
|----------------------|-----------------------------------------|
| Applied              | Application submitted                   |
| Shortlisted          | Resume/profile shortlisted              |
| Interview Scheduled  | Interview confirmed                     |
| Rejected             | Application not moved forward           |
| Selected             | Offer received 🎉                       |

---

## 🔧 Configuration

The server runs on port **8080** by default. You can override this with an environment variable:

```bash
PORT=3000 npm start
```

---

## 📌 Notes

- All application data is stored in the browser's `localStorage`. Clearing browser data will reset your records.
- No database or backend API is required — the Express server only serves the static `index.html` file.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

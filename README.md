
# 📁 ProMi - Projects Romi

A simple web-based project and client management tool. Ideal for freelancers or small businesses that want to efficiently track jobs, payments, and reports.

---

## ✨ Main Features

- 🔐 Simple login (no user database)
- 👥 Client management (add, view, delete)
- 📋 Add a project together with a client
- 💸 Payments: cash / transfer / QRIS
- 📊 Statistics: project status, revenue
- 🔍 Filter projects by status & payment
- 📖 Project change history
- 📆 Weekly & Monthly reports (ready to be extended)

---

## 🛠️ Tech Stack

- **Next.js** (pages-based)
- **MongoDB** via `mongodb` driver
- **Tailwind CSS** via CDN
- **Icon**: React Icons
---

## 🚀 How to Run

### 1. Clone the Repo
```bash
git clone https://github.com/romiwebdev/ProMi-project-manager.git
cd ProMi-project-manager
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment

Create a `.env.local` file:

```
MONGODB_URI=your_mongodb_connection_string
```

### 4. Run the App

```bash
npm run dev
```

Open at: [http://localhost:3000](http://localhost:3000)

---

## 📝 Usage Notes

* Login only requires typing anything in the password field (no complex authentication).
* All data is stored in MongoDB: `clients`, `projects`, and `activityLogs`.
* The weekly/monthly report and PDF export features can be further developed.

---

## 🧑‍💻 Contributing

Pull requests are very welcome! You can help with:

* Report export to PDF
* Deadline reminder feature
* More detailed client/project search
* Email/password-based login auth

---

## 📄 License

MIT License.

---

> Made with a productive spirit by Romi.
 
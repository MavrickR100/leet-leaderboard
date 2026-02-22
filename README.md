# Friends LeetCode Dashboard 🚀

A responsive leaderboard application that tracks and ranks LeetCode problem-solving activity among peers to foster competitive learning and DSA practice.

🔗 **Live Demo:**  [
https://mavrickr100.github.io/friends-leetcode-dashboard/](https://mavrickr100.github.io/leet-leaderboard/)

---

## 📊 What This Dashboard Shows

For each LeetCode user, the dashboard displays:

- **Total Problems Solved**
- **Global Ranking**
- **Problems Solved by Difficulty**
    - Easy
    - Medium
    - Hard
- **Recent Submissions (latest 3)**
    - Problem title
    - Submission status (Accepted / Failed)
    - Submission date & time
- **Leaderboard Ranking**
    - Users are automatically ranked based on total problems solved
    - Top 3 users get special rank badges 🥇🥈🥉

Each username links directly to the user's **LeetCode profile**.

---

## 🛠️ How It Works

- Built using **pure HTML, CSS, and JavaScript**
- Fetches live data from public LeetCode APIs:
    - `leetcode-api-faisalshohag.vercel.app`
    - `leetcode-stats-api.herokuapp.com`
- No backend required
- Fully client-side and lightweight
- Responsive UI for mobile, tablet, and desktop

---

## 👥 Adding or Updating Users

Edit the `USERS` array in `index.html`:

```js
const USERS = [
  { username: 'leetcode_username', displayName: 'Display Name' }
];
```
Just commit the change and refresh the page.

## 🌐 Hosting Using GitHub Pages

You can host this dashboard for **free** using GitHub Pages.

### Step-by-step Setup

#### 1. Push files to GitHub
- Ensure `index.html` is in the **root** of the repository
- Repository must be **public**

#### 2. Enable GitHub Pages
- Go to your repository → **Settings**
- Click **Pages** (left sidebar)

#### 3. Configure Deployment
- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`
- Click **Save**

#### 4. Wait 1–2 minutes
- GitHub will build and deploy the site automatically

#### 5. Access Your Site
https://<your-username>.github.io/<repository-name>/

**Example:**
https://mavrickr100.github.io/friends-leetcode-dashboard/


---

## ⚠️ Notes & Limitations

- API availability depends on **third-party services**
- If an API is down, user data may **temporarily not load**
- Rate limits may apply
- No authentication required (only **public LeetCode profiles** are supported)

---

## ✨ Future Improvements (Ideas)

- Weekly / monthly progress comparison
- Charts & graphs (e.g., Chart.js)
- Dark / light theme toggle
- Manual refresh button
- Caching for faster load times

---

## 📄 License

This project is for **learning and personal use**.  
Feel free to **fork, modify, and enhance** it.

---

Made with ❤️ to stay consistent on LeetCode

---

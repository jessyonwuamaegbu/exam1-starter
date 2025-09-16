# Exam 1 – Starter

This folder gives you a tiny static site to practice the exact flow your exam expects.

## Run locally
1. Open the folder in **VS Code**.
2. Install the **Live Server** extension if you haven't.
3. Right–click `index.html` → **Open with Live Server**.

## Push to GitHub (VS Code)
1. Click **Source Control** (branch icon).
2. Click **Initialize Repository**.
3. Type a commit message like `first commit` → **Commit**.
4. Click **Publish Branch** → choose **GitHub** and make the repo **Public** or **Private**.
5. Confirm when VS Code asks to create the repo on GitHub.

## Deploy to Vercel
1. Go to **vercel.com** and sign in with GitHub.
2. Click **Add New… → Project → Import** your GitHub repo.
3. Framework: **Other** (static). No special build settings.
4. Deploy. You'll get a `*.vercel.app` URL.

## Connect your domain (optional but often required)
1. In your Vercel project → **Settings → Domains** → **Add** your domain.
2. Copy the DNS records Vercel shows you and paste them into your registrar's DNS manager (e.g., GoDaddy).
3. Wait for propagation; Vercel will show a green check when it's live.

Good luck! You got this.

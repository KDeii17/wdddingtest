# Dear Guest (Wedding Invitation)

This repository contains a wedding invitation web app built with React + TypeScript + Tailwind CSS. You can run it locally, customize it, and deploy it to make it available to your guests.

## 🛠️ Run the app locally

Requirements:
- Node.js (v18+) or later
- npm

```sh
# 1) Clone this repo
git clone <YOUR_REPO_URL>

# 2) Enter the project folder
cd <YOUR_PROJECT_FOLDER>

# 3) Install dependencies
npm install

# 4) Start the development server
npm run dev
```

Then open the local URL shown in the terminal (usually `http://localhost:5173`).

## 🧩 Customize the project

- Edit pages under `src/pages/` (e.g., `InvitationPage.tsx`).
- Update text, images, and styling in `src/components/wedding/`.
- Update global styles in `src/index.css` and `src/App.css`.

## 🚀 Deploy to production

This is a standard Vite React app, so you can deploy it to any static hosting provider.

### Option A — Vercel (recommended)
1. Create a Vercel account: https://vercel.com/
2. Import this repository.
3. Use the default settings (Framework: `Vite`, Build command: `npm run build`, Output directory: `dist`).

### Option B — Netlify
1. Create a Netlify account: https://app.netlify.com/
2. Link your Git repository.
3. Set build command to `npm run build` and publish directory to `dist`.

### Option C — Manual (`npm run build` + static host)

```sh
npm run build
# then deploy the `dist/` folder to any static host (GitHub Pages, S3, etc.)
```

## 📌 Next steps (make it yours)

1. Pick a name for your app and replace the title in `index.html`.
2. Replace images in `public/` and update the open graph metadata (OG tags) in `index.html`.
3. Update the event details in `src/pages/InvitationPage.tsx`.

---

If you'd like, tell me the name you want for your project and which hosting provider you'd like to use, and I can help you apply those changes and get it live.

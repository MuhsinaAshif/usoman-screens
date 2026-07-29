# United Securities — Mobile Screen Review

Public HTML preview of investor mobile app screens.

## Open locally

Open `index.html` or `mobile-screens-all-flows.html` in Chrome / Edge.

## Publish on GitHub Pages (public link for anyone)

### 1. Create a public repo on GitHub

1. Go to [https://github.com/new](https://github.com/new)
2. Repository name example: `usoman-mobile-screens`
3. Visibility: **Public** (required so anyone can open the Pages link without login)
4. Do **not** add a README (this folder already has one)
5. Click **Create repository**

### 2. Push this folder

In PowerShell:

```powershell
cd D:\Projects_Dev_Tamimah_2026\UnitedSecurities\usoman-mobile-screens-pages
git init
git add .
git commit -m "Add United Securities mobile screen review HTML"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/usoman-mobile-screens.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username (or org).

### 3. Turn on GitHub Pages

1. Open the repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
3. Click **Save**
4. Wait 1–2 minutes

### 4. Share the public link

After Pages is ready, share either:

- `https://YOUR_USERNAME.github.io/usoman-mobile-screens/`
- `https://YOUR_USERNAME.github.io/usoman-mobile-screens/mobile-screens-all-flows.html`

Anyone with the link can open it — no login needed — because the repo is **Public**.

## Important

- Keep the `mobile-screens/assets/` folder with the HTML. Without it, images break.
- Private repos: only people with GitHub access can see Pages (and free personal accounts often need Public for Pages).

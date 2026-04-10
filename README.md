# cloudhaven-website

## 🚀 Deploy to Vercel (One-Click)

1. **Connect GitHub repo to Vercel**:
   ```
   npm i -g vercel
   cd cloudhaven-site
   vercel login
   vercel --prod
   ```

2. **Or GitHub Integration**:
   - Push to GitHub
   - vercel.com → New Project → Import GitHub repo
   - Deploy!

**Production URL**: Auto-assigned or custom domain.

**Build Command**: `npm run build` (auto-detected)
**Output Directory**: `.next`
**Install Command**: `npm ci`

## Local Development
```bash
cd cloudhaven-site
npm install
npm run dev
```

Open http://localhost:3000

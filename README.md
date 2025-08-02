# CoCreate – Vision Composer

A tool to help people articulate and share visions for a regenerative, collaborative future.

## 🧰 Tech Stack
- Next.js
- TailwindCSS
- Supabase (or Firebase)
- OpenAI GPT-4o API
- Magic link or wallet login (optional web3)

## 🚀 Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Create environment file
```bash
cp .env.local.example .env.local
# then fill in real values in .env.local
```

### 3. Run development server
```bash
npm run dev
```

### 4. Git workflow
```bash
git add .
git commit -m "Describe your change"
git push
```

## 🧪 Scripts
- `npm run dev` – start dev server  
- `npm run build` – build for production  
- `npm run lint` – run ESLint  
- `npm run format` – format with Prettier  

## 📦 Features
- Vision Mapping guided by AI  
- Project planning + roadmap  
- Auth-ready (Supabase)  

## 📁 Structure
- `pages/` – Next.js pages  
- `lib/` – helpers (e.g., Supabase client)  
- `.github/workflows/ci.yml` – CI pipeline  

## 🛡 Security
Do **not** commit `.env.local`. Use `.env.local.example` as a template.


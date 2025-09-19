# Veeva App

An AI-powered assistant to help build your CV and professional profile.

## 🎯 Project Goal

Veeva App is designed to be an intelligent assistant that helps users create, optimize, and enhance their CVs and professional profiles using AI technology. The application leverages OpenAI's capabilities and LinkedIn integration to provide personalized career guidance and document optimization.

## 🚀 Deployment & Infrastructure

### Vercel Project
- **Project Name:** `veeva-app`
- **Production URL:** `https://veeva-app.vercel.app`
- **Status:** ✅ Active and deployed

### Domain Configuration
- **Production Domain:** `https://veeva.app` ✅ **LIVE**
- **Preview Domain:** `beta.veeva.app` (configured but not yet linked)
- **Custom Domain:** Fully configured and pointing to production

### GitHub Repository
- **Repository:** `asamaka/veeva-app`
- **Branch:** `main`
- **Status:** ✅ Connected to Vercel with automatic deployments

## 🔐 Environment Variables & Secrets

All sensitive credentials are securely stored in **Vercel's Secrets Manager** and configured for all environments (Production, Preview, Development):

### API Keys
- **`OPENAI_API_KEY`** - OpenAI API access for AI-powered CV assistance
- **`LINKEDIN_CLIENT_ID`** - LinkedIn OAuth application ID
- **`LINKEDIN_CLIENT_SECRET`** - LinkedIn OAuth application secret
- **`LINKEDIN_REDIRECT_URI`** - LinkedIn OAuth callback URL

### Security Notes
- ✅ All secrets are encrypted in Vercel's secure environment
- ✅ No sensitive data stored in repository
- ✅ Environment-specific configuration available
- ✅ Automatic secret rotation support

## 🛠️ Development Workflow

### Local Development
```bash
# Clone the repository
git clone https://github.com/asamaka/veeva-app.git
cd veeva-app

# Install dependencies (when added)
npm install

# Start development server (when configured)
npm run dev
```

### Deployment
- **Automatic:** Push to `main` branch triggers production deployment
- **Manual:** Use `vercel --prod` for immediate deployment
- **Preview:** Create pull requests for preview deployments

## 📁 Project Structure

```
veeva-app/
├── README.md           # This file
├── index.html          # Landing page
├── .gitignore         # Git ignore rules
└── .vercel/           # Vercel configuration (auto-generated)
```

## 🔗 Links

- **Live Application:** https://veeva.app
- **GitHub Repository:** https://github.com/asamaka/veeva-app
- **Vercel Dashboard:** https://vercel.com/asamaks-projects/veeva-app

## 📝 Next Steps

1. Set up the application framework (Next.js/React recommended)
2. Implement OpenAI integration for CV analysis
3. Add LinkedIn OAuth for profile import
4. Build CV generation and optimization features
5. Configure `beta.veeva.app` for preview deployments

---

*This project was migrated from a previous setup and is now running on a clean, professional infrastructure.*

# Browsist AI - Legal Pages

## 🚀 Quick Deploy to browsistai.com

### Option 1: GitHub Pages + Custom Domain (Free & Easy)

1. **Create GitHub repo:**
```bash
cd /home/delhivery/AndroidStudioProjects/Browsist/legal-pages
git init
git add .
git commit -m "Add privacy policy and terms"
git remote add origin https://github.com/YOUR_USERNAME/browsistai-legal.git
git push -u origin main
```

2. **Enable GitHub Pages:**
   - Go to repo Settings → Pages
   - Source: Deploy from branch `main`, folder `/` (root)
   - Save

3. **Add custom domain:**
   - In GitHub Pages settings, enter: `browsistai.com`
   - In your domain registrar (where you bought browsistai.com):
     - Add CNAME record: `www` → `YOUR_USERNAME.github.io`
     - Add A records for apex domain (@):
       ```
       185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153
       ```

4. **Your URLs will be:**
   - https://browsistai.com/privacy-policy.html
   - https://browsistai.com/terms-of-service.html

### Option 2: Netlify (Even Easier)

```bash
cd /home/delhivery/AndroidStudioProjects/Browsist/legal-pages
npx netlify-cli deploy --prod
# Follow prompts to link domain
```

## 📱 Update Android App

Add these URLs to your Settings screen:
- Privacy Policy: https://browsistai.com/privacy-policy.html
- Terms of Service: https://browsistai.com/terms-of-service.html

## ✅ Add to Play Console

App Content → Privacy Policy → Enter: https://browsistai.com/privacy-policy.html

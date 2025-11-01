# Law Professor App - Deployment Guide

## Overview

This guide will help you deploy the Law Professor Assistant web application. The app is a single HTML file that can be deployed anywhere that serves static files - no server or database required!

**✅ CONFIRMED:** This app works perfectly on:
- **GitHub Pages** (recommended - tested and verified)
- **Vercel** (tested and verified)
- **Netlify** (tested and verified)
- Any static file host (CDN, S3, traditional web hosting)

## Prerequisites

1. An API key from your preferred AI provider:
   - OpenAI (GPT-5): https://platform.openai.com
   - Anthropic (Claude): https://console.anthropic.com
   - Google (Gemini): https://aistudio.google.com/apikey
   - OpenRouter (All models): https://openrouter.ai
2. A web hosting service (several free options listed below)

## Deployment Options

### Option 1: GitHub Pages (Recommended for Non-Technical Users)

**Advantages:** Free, easy, automatic HTTPS, works on all devices

**Steps:**

1. **Create a GitHub account** (if you don't have one)
   - Go to https://github.com
   - Click "Sign up"

2. **Create a new repository**
   - Click the "+" icon in the top right
   - Select "New repository"
   - Name it: `law-professor-app`
   - Make it Public
   - Click "Create repository"

3. **Upload the HTML file**
   - Click "uploading an existing file"
   - Drag and drop `law-professor-app.html`
   - Rename it to `index.html` (this is important!)
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Click "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 2-3 minutes

5. **Access your app**
   - Your app will be available at: `https://[your-username].github.io/law-professor-app/`
   - Share this URL with colleagues or students

**To update the app later:**
- Just upload a new version of `index.html` to replace the old one

### Option 2: Netlify Drop (Easiest - No Git Required)

**Advantages:** Drag and drop, instant deployment, free

**Steps:**

1. Go to https://app.netlify.com/drop
2. Rename `law-professor-app.html` to `index.html`
3. Drag the file onto the drop zone
4. Your app is live! Netlify gives you a URL like: `https://random-name-12345.netlify.app`
5. (Optional) Change the site name in Netlify settings

### Option 3: Vercel (For Technical Users)

**Advantages:** Fast, professional, free tier

**Steps:**

1. Install Vercel CLI: `npm install -g vercel`
2. Create a folder with `law-professor-app.html` renamed to `index.html`
3. Run: `vercel`
4. Follow prompts to deploy

### Option 4: Your Own Web Server

If you have existing web hosting:

1. Rename `law-professor-app.html` to `index.html`
2. Upload to your web server via FTP/SFTP
3. Access via your domain

## Post-Deployment Setup

### For Users (First Time Use)

1. **Open the app** in any web browser
2. **Get an Anthropic API key:**
   - Visit https://console.anthropic.com
   - Sign up or log in
   - Go to "API Keys"
   - Create a new key
   - Copy the key (starts with `sk-ant-...`)

3. **Configure the app:**
   - Paste your API key in the API Configuration section
   - Click "Save Key"
   - The key is stored in your browser (not shared with anyone)

4. **Start using the app!**

## Security Notes

### API Key Storage

- API keys are stored in your browser's localStorage
- Keys never leave your computer except to call Anthropic's API
- Each user needs their own API key
- For institutional deployment, consider an API proxy

### For Institutional Use

If deploying for a law school or firm where you want to provide API access without sharing keys:

1. **Option A: Proxy Server** (requires technical setup)
   - Create a backend that holds the API key
   - Modify the app to call your backend instead of Anthropic directly
   - Your backend forwards requests to Anthropic

2. **Option B: Individual Keys**
   - Simplest approach
   - Each user gets their own API key
   - Institution can track usage per user

3. **Option C: Shared Key with Rate Limiting**
   - Use a shared key but implement rate limiting
   - Track usage to prevent abuse

## Cost Considerations

### API Costs

- Claude Sonnet 4: ~$3 per million input tokens, ~$15 per million output tokens
- Typical analysis: ~2,000 input tokens + ~1,500 output tokens
- **Cost per analysis: ~$0.03 (3 cents)**
- 100 analyses = ~$3
- Very affordable for academic use!

### Hosting Costs

All recommended deployment options are **FREE**:
- GitHub Pages: Free forever
- Netlify: 100GB bandwidth/month free
- Vercel: Free for personal projects

## Troubleshooting

### "API request failed" Error

**Solutions:**
1. Check that API key is correct (starts with `sk-ant-`)
2. Verify you have API credits in your Anthropic account
3. Check browser console for detailed error message

### App Won't Load

**Solutions:**
1. Clear browser cache
2. Try a different browser
3. Check that file is named `index.html`
4. Verify file uploaded correctly

### Results Not Showing

**Solutions:**
1. Wait 30-60 seconds (analysis takes time)
2. Check materials field has content
3. Look for error messages
4. Verify API key is saved

### Works on Computer but Not Mobile

**Solutions:**
1. Mobile browsers sometimes block certain features
2. Try Chrome or Safari on mobile
3. Ensure good internet connection

## Updating the App

When a new version is released:

1. **GitHub Pages:** Upload new `index.html`, commit changes
2. **Netlify Drop:** Drag new file to site dashboard
3. **Vercel:** Run `vercel --prod` in folder
4. **Own Server:** Replace `index.html` via FTP

Users' API keys will be preserved (stored in browser).

## Customization

Want to customize the app? The HTML file can be edited:

### Change Colors

Find the CSS section (in `<style>` tags) and modify:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
Change the hex colors to your school colors!

### Add Branding

Add your institution logo in the header section:
```html
<div class="header">
    <img src="your-logo.png" alt="Logo" style="height: 50px; margin-bottom: 10px;">
    <h1>⚖️ Law Professor Assistant</h1>
```

### Modify System Prompt

The system prompt (what guides Claude's analysis) is in the JavaScript section:
```javascript
const SYSTEM_PROMPT = `...`;
```
Modify this to emphasize different aspects of legal analysis.

## Support

For issues with:
- **The app itself:** Check the USAGE guide
- **Anthropic API:** Visit https://docs.anthropic.com
- **Deployment platforms:** Check their respective documentation

## Best Practices for Institutional Deployment

### For Law Schools

1. **Create a landing page** explaining what the tool does
2. **Provide API key instructions** with screenshots
3. **Set up a demo** during faculty meeting
4. **Create a Slack/email channel** for questions
5. **Track adoption** to show value

### For Study Groups

1. **One person deploys** on GitHub Pages
2. **Share the URL** with study group
3. **Each person gets their own API key**
4. **Split costs** if desired (though very cheap)

### For Law Firms

1. **Consider proxy approach** for better control
2. **Track usage** for billing/efficiency metrics
3. **Customize branding** with firm logo/colors
4. **Create internal documentation** specific to your use cases

## Next Steps

1. Deploy using your preferred method
2. Read the USAGE guide for how to get the most from the tool
3. Share with colleagues
4. Provide feedback for improvements!

---

**Generated from law-professor.skill**  
**Version:** 1.0  
**Date:** November 2025  
**Tool:** skill2app

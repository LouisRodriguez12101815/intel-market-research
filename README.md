# Intel Corporation Market Research - GitHub Pages

This repository contains a comprehensive market research analysis of Intel Corporation, including product lifecycle analysis and product mix strategy recommendations.

## 🌐 Live Site

Once deployed, your site will be available at: `https://[your-username].github.io/intel-market-research/`

## 📋 Contents

### Assignment 1: Product Life Cycle Analysis
- **Flagship Product:** Intel Core Ultra Series 3 Processors
- **Launch Date:** January 27, 2026
- **Current Stage:** Growth
- Includes detailed 450-character and 500-character product descriptions

### Assignment 2: Product Mix Strategy
Three strategic recommendations:

1. **NEW PRODUCT:** Intel Core Ultra X AI Creator Edition (Q4 2026)
   - Premium AI content creation processor
   - Target: Professional creators ($80K-$200K income)
   - Response to AMD dominance in creative workstation market

2. **MODIFY PRODUCT:** Intel Xeon 6 AI Accelerator Refresh (Q2 2026)
   - Integrate 150+ TOPS NPU for AI inference
   - Counter AMD EPYC and NVIDIA Grace CPU threats
   - Target: Enterprise data centers

3. **ELIMINATE PRODUCT:** Intel Optane Persistent Memory (Q4 2026 phase-out)
   - Market failure (<1% Intel revenue)
   - Eliminate $800M annual losses
   - Reallocate resources to AI development

## 🚀 Deploying to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right → "New repository"
3. Name your repository: `intel-market-research`
4. Make it **Public**
5. Do NOT initialize with README (we already have one)
6. Click "Create repository"

### Step 2: Push Your Files to GitHub

Open PowerShell/Terminal in the `intel-market-research-site` folder and run:

```bash
cd "C:\Users\LouisRodriguez\Downloads\carbone_01272026\intel-market-research-site"

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Intel market research analysis"

# Add your GitHub repository as remote (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/intel-market-research.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select:
   - **Branch:** main
   - **Folder:** / (root)
5. Click "Save"
6. Wait 1-2 minutes for deployment
7. Your site will be live at: `https://[YOUR-USERNAME].github.io/intel-market-research/`

## 📁 File Structure

```
intel-market-research-site/
├── index.html          # Main website file
├── styles.css          # Styling and layout
└── README.md           # This file
```

## 🎨 Features

- **Responsive Design:** Works on desktop, tablet, and mobile
- **Sticky Navigation:** Easy access to all sections
- **Color-Coded Strategies:** Green (New), Yellow (Modify), Red (Eliminate)
- **Product Lifecycle Visualization:** Interactive stage breakdown
- **Professional Intel Branding:** Uses official Intel blue colors
- **Print-Friendly:** Optimized for PDF export

## 📊 Research Methodology

### Data Sources
- Intel corporate website & annual reports
- CES 2026 product announcements
- Intel newsroom & press releases
- Social media analysis (LinkedIn, YouTube, Facebook)
- Competitive market data (AMD, NVIDIA, Qualcomm)

### Frameworks Applied
- Product Life Cycle Analysis
- Product Mix Strategy (Add/Modify/Eliminate)
- Target Market Segmentation
- Organizational Objective Alignment

## 🔧 Customization

### Changing Colors
Edit `styles.css` and modify the CSS variables:
```css
:root {
    --intel-blue: #0071c5;
    --intel-navy: #003d5b;
    /* ... other colors ... */
}
```

### Adding Content
Edit `index.html` to add new sections or modify existing content.

## 📄 License

This research was conducted for academic purposes. Intel, Core Ultra, Xeon, and Optane are trademarks of Intel Corporation.

## 👤 Author

Louis Rodriguez  
Market Research Analysis  
January 2026

---

## 🆘 Troubleshooting

### Site Not Loading?
- Wait 2-3 minutes after enabling GitHub Pages
- Check that repository is Public
- Verify branch is set to "main" in Pages settings
- Clear browser cache and try again

### Need to Update Content?
```bash
# Make your changes to index.html or styles.css
git add .
git commit -m "Update content"
git push
```
Changes will appear on the live site within 1-2 minutes.

### Want a Custom Domain?
1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In repository Settings → Pages → Custom domain
3. Enter your domain and click Save
4. Configure DNS with your domain provider

---

**Last Updated:** January 28, 2026

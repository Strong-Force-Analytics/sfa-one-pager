# Strong Force Analytics - Project Documentation

This repository contains the source code for the official **Strong Force Analytics** landing page. The site is a static one-pager hosted via **GitHub Pages** and mapped to the custom domain: [strongforceanalytics.com](https://strongforceanalytics.com).

## 🌐 Live Site

**Public URL:** [https://strongforceanalytics.com](https://strongforceanalytics.com)

---

## 🚀 Quick Deployment Guide

To update the website, you only need to ensure your main file is named `index.html` and push it to the `main` branch.

### 🛠 Local Development Workflow

If you are working on your local machine, follow these standard Git commands:

#### 1. Pull the Latest Changes

```bash
git pull origin main
```

#### 2. Make Your Edits

Update your `index.html` file with the desired changes.

#### 3. Stage and Commit

```bash
git add .
git commit -m "Update site content"
```

#### 4. Push to Live

```bash
git push origin main
```

---

## ⚙️ Infrastructure Configuration

### 1. DNS Settings (GoDaddy)

The domain is connected to GitHub using the following DNS records. Do not change these unless moving to a different hosting provider.

| Type | Name | Value / Data | TTL |
|------|------|-------------|-----|
| A | `@` | `185.199.108.153` | 1/2 Hour |
| A | `@` | `185.199.109.153` | 1/2 Hour |
| A | `@` | `185.199.110.153` | 1/2 Hour |
| A | `@` | `185.199.111.153` | 1/2 Hour |
| CNAME | `www` | `Strong-Force-Analytics.github.io` | 1/2 Hour |

### 2. GitHub Pages Settings

- **Branch:** `main`
- **Folder:** `/ (root)`
- **Custom Domain:** `strongforceanalytics.com`
- **Enforce HTTPS:** Enabled (Ensures a secure 🔒 connection)

---

## 📁 Repository Structure

```
.
├── index.html          # The homepage (must remain in the root directory)
├── README.md           # This documentation file
```

### File Descriptions

- **`index.html`**: The main landing page. This file must be in the root directory for GitHub Pages to serve it correctly.
- **`README.md`**: Project documentation and deployment instructions (this file).
- **`/assets`**: Optional directory for organizing images, logos, stylesheets, JavaScript files, or other static assets.

---

## 📝 Notes

- Maintained by Strong Force Analytics
- For any questions or issues, please contact the project maintainers
- Always ensure HTTPS is enforced for security

---

**Last Updated:** April 2026

# Welcome to Nimble Partner Website

Welcome! This guide will show you how to update the content of your website using GitHub's web interface.
You do not need any special software or command line skills—just your web browser and a GitHub account.

---

## Table of Contents

- [Introduction](#introduction)
- [Step-by-Step Instructions](#step-by-step-instructions)
  - [1. Log In to GitHub](#1-log-in-to-github)
  - [2. Navigate to the Repository](#2-navigate-to-the-repository)
  - [3. Find the File to Edit](#3-find-the-file-to-edit)
  - [4. Edit the File](#4-edit-the-file)
  - [5. Commit Your Changes](#5-commit-your-changes)
- [Tips and Troubleshooting](#tips-and-troubleshooting)
- [Additional Information](#additional-information)

---

## Introduction

This documentation explains how to update the text, images, and other content of your website.

The website is built with [Hugo](https://gohugo.io/) and uses [Tailwind CSS](https://tailwindcss.com/).
Whenever you want to change a page or update information, you’ll be editing Markdown or configuration files directly on GitHub.
The changes you make will be automatically published to the live website.

---

## Step-by-Step Instructions

### 1. Log In to GitHub

1. Open your web browser and go to [GitHub](https://github.com/).
2. Click **Sign in** at the top right corner and enter your username and password.

### 2. Navigate to the Repository

1. Once logged in, go to your repository where the website content is stored (for example: `github.com/yourusername/your-website`).
2. You can use the search bar or click on **Your repositories** from your profile to find it.

### 3. Find the File to Edit

1. In the repository, look for the **content folder** or the specific file you want to update (most website pages are written in Markdown, with a `.md` extension).
2. Click on the file you want to change. For example, if you want to update the "About" page, click on the file named `about.md` (or a similar name) located in the `content` directory.

### 4. Edit the File

1. Once you are viewing the file, look for the **pencil icon** (✏️) near the top right of the file view. Click this icon to enter the editor.
2. The file will open in GitHub’s built-in editor. Make your changes directly in the text area. You can add or change text, update links, or even change image paths if needed.
3. Use the formatting tools (if available) to help you with headings, lists, and other text styles.

### 5. Commit Your Changes

1. After you finish editing, scroll down to the **"Commit changes"** section below the editor.
2. In the **"Commit changes"** box:
   - **Title:** Enter a short description of your update (for example, "Update About page content").
   - **Description (optional):** You can add more details about the changes if you like.
3. Choose **"Commit directly to the main branch"** if you are ready for the changes to go live. (If your repository uses Pull Requests, follow your team's process.)
4. Click the **"Commit changes"** button.

Once committed, your changes will be automatically built and published to your live website.

---

## Tips and Troubleshooting

- **Preview Before Committing:** If your repository is connected to a preview service (like Netlify or Vercel), you might be able to see a preview of your changes before they go live.
- **Editing Multiple Files:** Repeat these steps for any other pages or files you wish to update.
- **Need Help?** If you’re unsure about any step, feel free to ask a colleague or contact your website administrator for assistance.
- **Don’t Worry About Technical Jargon:** Terms like "commit," "repository," and "Markdown" might sound technical, but just think of them as “saving your changes” in an online document.

---

## Additional Information

- **Content Files:** Your website content is primarily written in Markdown, which is a simple way to format text.
- **Configuration Files:** If you need to update things like the site title or theme settings, these are usually in files like `config.toml` or files under the `config` directory. If you are not sure what to change, please consult with your website administrator.
- **Need More Customization?** For more advanced edits (like changing layouts or styles), you might need help from someone with more technical expertise. This guide is meant for content updates only.

---

Thank you for helping keep our website up to date! If you find any part of this guide confusing or have suggestions for improvement, please reach out so we can make it even easier to use.

---

_This document is maintained as part of our website project. Happy editing!_

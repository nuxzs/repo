# All-in-One Kodi Repository Hub

A simple web page that collects multiple Kodi repository links in one place. Add one source and access all repositories without installing them individually.

## 📖 What This Is

This is a **hosted web page** that displays Kodi repository URLs. Instead of adding multiple repository sources to your Kodi setup, you can use this page to:

- View all available repository links in one location
- Copy repository URLs easily for use in Kodi
- Access them from any device via the web

## 🔗 Visit the Hub

Open the web page to see all available repositories and copy their URLs:

[**All-in-One Kodi Repository Hub**](https://nuxzs.github.io/repo/)

## 💡 How to Use

1. Visit the website
2. Find the repository you want to add
3. Copy the repository URL
4. Add it as a source in Kodi (File Manager → Add Source)
5. Install the repository from ZIP file

## 📦 What's Included

The hub displays links to multiple Kodi repositories with:
- Repository name
- Description
- Direct URL for easy copying
- Status indicator

## 🛠️ How It Works

- Pure HTML/CSS/JavaScript - no dependencies
- Repository data is stored in a simple JavaScript array
- Easy to modify and add new repositories
- Copy-to-clipboard functionality with visual feedback

## ✏️ Customizing

To add or modify repositories, edit the `repositories` array in `index.html`:

```javascript
const repositories = [
    {
        name: 'Repository Name',
        description: 'Short description',
        url: 'https://your-repo-url.com/',
        status: 'Active'
    },
    // Add more repositories here
];
```

## 📄 Files

- `index.html` - The main web page with all styling and functionality
- `README.md` - This file

## 🎯 Purpose

This repository is a **link aggregator for Kodi repositories**, not a Kodi addon repository itself. It makes it easier to manage and share multiple repository sources in one place.

---

Made for Kodi enthusiasts who want a cleaner way to manage multiple repository sources.

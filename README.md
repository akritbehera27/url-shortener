
# Url-Shortener
A lightweight, self-hosted URL shortener built with Python and static site hosting. This solution gives you complete control over your shortened links without relying on third-party services. Note when you push your code to a server, make sure that its privacy respecting and safe as you might be shortning some senstive links .So do give it a try...

### Features
- Self-hosted - No external dependencies or third-party tracking
- Full control - Manage all your URLs with complete ownership
- Simple setup - Deploys as a static site with Python backend
- Custom slugs - Choose your own short codes

### Tech Stack
- **Backend**: Python
- **Frontend**: Static HTML/JS (compatible with GitHub Pages, Netlify, Vercel)
- **Database**: None For minimalism
- **Hosting**: Any static site provider
- **Logs**: Logs are Stored at logs/*
  

If you are further pushing it to git make sure that your logs and shorturls .html files are not being tracked so to ensure privcy use this command to ignore change to logs

```
 # Clone the repository
git clone https://github.com/yourusername/url-shortener.git
cd url-shortene
git update-index --skip-worktree logs/*

```


### Prerequisites
This program is too light weight it only requires these...
- Python 3.8+
- pip package manager
- Any Static Webhosting

  
### Installation

```
 # Clone the repository
git clone https://github.com/yourusername/url-shortener.git
cd url-shortene
python RunMe.py
 # Install dependencies based on your requirement
```

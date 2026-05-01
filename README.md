# My Netlify CMS Site

A simple HTML website with Netlify CMS for content management.

## File Structure

```
netlify-site/
├── index.html          ← Your homepage
├── netlify.toml        ← Netlify config
├── admin/
│   ├── index.html      ← CMS interface loader
│   └── config.yml      ← CMS collections & settings
└── _posts/             ← Your blog posts (Markdown) go here
```

## 🚀 Deploy in 5 Steps

### 1. Push to GitHub
Create a new GitHub repo and push this folder to it.

### 2. Connect to Netlify
- Go to [netlify.com](https://netlify.com) and log in
- Click **"Add new site" → "Import an existing project"**
- Connect your GitHub repo
- Leave build settings as-is (no build command needed)
- Click **Deploy**

### 3. Enable Netlify Identity
- In your Netlify dashboard go to **Site settings → Identity**
- Click **"Enable Identity"**
- Under **Registration**, choose **"Invite only"** (recommended)

### 4. Enable Git Gateway
- Still in Identity settings, scroll to **Services → Git Gateway**
- Click **"Enable Git Gateway"**

### 5. Invite yourself
- Go to **Identity tab** in your dashboard
- Click **"Invite users"** and enter your email
- Accept the invite — you'll set a password and can now log into `/admin/`

## ✏️ Using the CMS

Visit `https://your-site.netlify.app/admin/` and log in.  
You can create/edit/delete blog posts and pages from there.  
Each save commits directly to your GitHub repo.

## Customising

- **Add collections**: Edit `admin/config.yml` to add new content types
- **Style the site**: Edit `index.html` CSS
- **Add pages**: Create new `.html` files in the root
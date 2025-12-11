# Robo World Blog

Welcome to the **Robo World** blog source code! This is a static site built with [Jekyll](https://jekyllrb.com/) and managed with [Decap CMS](https://decapcms.org/).

## 🚀 How to Write a Post

You can write posts without touching any code!

1.  Navigate to your site's admin page: `https://robo-world-rb.github.io/admin/`
2.  Login with your GitHub account.
3.  Click **"New Blog"** to start writing.
4.  Fill in the **Title**, **Description**, and **Body**.
5.  You can also upload an **Image**.
6.  Click **"Publish"** to save. This will automatically update your website!

## ⚙️ Initial Setup (Important!)

To enable the "Login with GitHub" feature, you need to configure GitHub to allow Decap CMS to access your repository.

**Option A: Simplified Setup (recommended if prompted)**
If you see a prompt to authorize `Decap CMS` or `Netlify Identity`, follow it.

**Option B: Manual OAuth Setup (Standard)**
If you get an authentication error, you may need to register an OAuth application on GitHub.
1.  Go to your GitHub Settings > Developer settings > OAuth Apps.
2.  Register a new application.
3.  Set the **Homepage URL** to `https://robo-world-rb.github.io`.
4.  Set the **Authorization callback URL** to `https://robo-world-rb.github.io/admin/`.
5.  *Note: Since this is a static site on GitHub Pages without an external backend server, you typically need an external authentication service (like Netlify Identity) or a proxy. If you are hosting this purely on GitHub Pages, look into [Decap CMS on GitHub Pages guide](https://decapcms.org/docs/github-backend/).*

## 🛠 Local Development

If you want to run this locally:

1.  Install Ruby and Jekyll.
2.  Run `bundle install`.
3.  Run `bundle exec jekyll serve`.
4.  Open `http://localhost:4000`.

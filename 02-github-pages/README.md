# Task 2: Host a Personal Site with GitHub Pages

GitHub Pages turns a repository into a live website — for free. In this task, you will create a simple personal site that anyone can visit.

---

## Steps

1. On GitHub, click the **+** button (top right) and select **New repository**.
2. Name the repository **`your-username.github.io`** (replace `your-username` with your actual GitHub username, e.g., `janedoe.github.io`).
3. Make it **Public**.
4. Check **"Add a README file"**.
5. Click **Create repository**.
6. In your new repository, click **Add file** > **Create new file**.
7. In the "Name your file" field, type `index.html`.
8. Copy the starter HTML below and paste it into the editor. Replace the placeholder text in `[brackets]` with your own information:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 700px;
            margin: 50px auto;
            padding: 0 20px;
            line-height: 1.6;
            color: #333;
        }
        h1 {
            border-bottom: 2px solid #0366d6;
            padding-bottom: 10px;
        }
        a {
            color: #0366d6;
        }
        .section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>
    <h1>Welcome! I'm [Your Name]</h1>

    <div class="section">
        <h2>About Me</h2>
        <p>I'm a student currently learning [your field of study].
           I'm interested in [your interests].</p>
    </div>

    <div class="section">
        <h2>What I'm Learning</h2>
        <ul>
            <li>Git and GitHub</li>
            <li>[Add your own items]</li>
        </ul>
    </div>

    <div class="section">
        <h2>Links</h2>
        <ul>
            <li><a href="https://github.com/your-username">My GitHub Profile</a></li>
        </ul>
    </div>
</body>
</html>
```

9. Scroll down, type a commit message (e.g., "Add index.html"), and click **Commit changes**.
10. Go to your repository's **Settings** tab > click **Pages** in the left sidebar.
11. Under "Branch", make sure it says `main` and `/ (root)`. If not, select them and click **Save**.
12. Wait 1-2 minutes, then visit **`https://your-username.github.io`** in your browser. Your site is live.

> If the site does not load right away, wait a few more minutes and refresh. GitHub Pages can take up to 5 minutes for the first deployment.

---

## What You Can Do Next

- Edit the HTML to add more content about yourself.
- Add a `style.css` file for more styling and link it with `<link rel="stylesheet" href="style.css">` in the `<head>`.
- Add more pages (e.g., `projects.html`) and link between them.

---

## What to Submit

When you are done, your instructor will check:

- [ ] You have a repository named **`your-username.github.io`**.
- [ ] The repository contains an `index.html` file with **your own content** (not the default placeholder text).
- [ ] The site is **live and accessible** at `https://your-username.github.io`.

**Submit:** Your live site link (e.g., `https://janedoe.github.io`).

---

## Reference

- [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart)
- [GitHub Pages official site](https://pages.github.com/)

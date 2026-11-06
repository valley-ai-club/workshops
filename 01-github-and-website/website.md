# Your website

[Workshop 1](README.md) · Office hours, right after [Part 1: GitHub](github.md)

Put your own page on the web, for free, with **GitHub Pages**.
Your website's address will be:

```
https://YOUR-USERNAME.github.io
```

By the end you will have:

- [ ] a repository named `YOUR-USERNAME.github.io`
- [ ] a live website at that address
- [ ] a page that's really yours: your words, your colors, your projects

Like Part 1, everything here works in a web browser.

## Part 1: Create your website repository

1. On GitHub, click **+** → **New repository**.
2. **Repository name:** your username followed by `.github.io`.
   If your username is `alexcodes`, the name is `alexcodes.github.io`. It must match your username exactly.
3. Choose **Public** and check **Add a README file**.
4. Click **Create repository**.

## Part 2: Add your home page

1. Open the [starter page](starter-site/index.html), click **Raw**, select all, and copy.
2. Go back to your `YOUR-USERNAME.github.io` repository.
3. Click **Add file** → **Create new file**.
4. Name the file `index.html` (all lowercase). Browsers open this file first.
5. Paste the starter page into the big box.
6. Click **Commit changes…**, write a message like `Add starter home page`, and click **Commit changes**.

## Part 3: See it live

1. Wait 1–2 minutes. GitHub is building your site.
   You can watch its progress in your repository's **Actions** tab.
2. Visit `https://YOUR-USERNAME.github.io`.

Not showing up after a few minutes?

1. In your repository, go to **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set the branch to **main** and the folder to **/ (root)**, then click **Save**.
4. Wait a minute or two, then refresh your site.

## Part 4: Make it yours

Open `index.html` in your repository and click the **pencil icon** to edit.
Look for the ✏️ comments: those are the places to change. After each change, commit it,
wait a minute, and refresh your site.

1. Change the name, the emoji, and the one-line tagline.
2. Rewrite **About me** in your own words.
3. Pick a color pair from the 🎨 comment at the top, or choose your own.
4. In **Projects**, replace `YOUR-USERNAME` so the link goes to your `my-first-repo`.

### HTML in one minute

HTML uses **tags** to say what each piece of a page is. Most tags come in pairs: `<p>` opens and `</p>` closes.

| Tag | What it makes |
|-----|---------------|
| `<h1>…</h1>`, `<h2>…</h2>` | Big heading, smaller heading |
| `<p>…</p>` | A paragraph |
| `<a href="https://…">…</a>` | A link |
| `<ul>` with `<li>…</li>` inside | A bulleted list |
| `<img src="picture.jpg" alt="what's in the picture">` | An image |
| `<!-- … -->` | A comment: notes for you, hidden on the page |

The `<style>` section at the top is **CSS**. HTML says what's on the page; CSS says how it looks.

### Ideas if you finish early

- Add a section, like **Favorite books** or **Places I want to visit**. Copy a whole `<section> … </section>` block and change it.
- Add a picture: in your repository click **Add file** → **Upload files** and upload an image,
  then add `<img src="your-file-name.jpg" alt="describe the picture" width="300">` to `index.html`.
  Pick a picture that doesn't show your face, your home, or your school.
- Add a second page: create `projects.html` and link to it from your home page with `<a href="projects.html">My projects</a>`.
- Edit in a codespace (see [Part 1](github.md#option-a-github-codespaces-works-on-any-computer-including-chromebooks))
  and commit from the terminal.

## Before you share your site: safety check

Your site is public. Anyone on the internet can see it.

- [ ] Only your first name or a nickname
- [ ] No address, phone number, email, or school schedule
- [ ] No photos of your face, your home, or your school, unless a parent or guardian says it's OK

## Stuck?

| Problem | Try this |
|---------|----------|
| `404` page | Wait a couple of minutes. Check the file is named exactly `index.html` and the repository is named exactly `YOUR-USERNAME.github.io`. Then check **Settings** → **Pages** (Part 3). |
| My change doesn't show up | Wait a minute, then hard-refresh: Ctrl+Shift+R (Cmd+Shift+R on a Mac). |
| The page looks broken or text disappeared | A tag is probably missing its closing tag, like a `<p>` without `</p>`. Open your repository's history, click your last commit, and compare. |
| My image doesn't show | The file name in `src="…"` must match the uploaded file exactly, including capital letters and `.jpg` vs `.png`. |

## Next

You now have a home for your work. In the coming workshops you'll add data projects to it.

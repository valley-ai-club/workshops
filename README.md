# Valley AI Club Workshops

Lessons, exercises, and starter files for the [Valley AI Club](https://valleyaiclub.org/)
AI & data science workshop series, for students in grades 7–12.

Each session has **1 hour of teaching** and **1 hour of hands-on office hours**.
No coding experience is needed.

## Sessions

| # | Session | What you'll make | Tools |
|---|---------|------------------|-------|
| 1 | [GitHub](01-github/) | A repository and your first commit | GitHub, Git |
| 2 | [Build a website](02-website/) | Your own page on the web | HTML, GitHub Pages |
| 3 | [Python, R & datasets](03-python-r-datasets/) | Load a dataset and explore its columns | Colab, pandas |
| 4 | [Data wrangling](04-data-wrangling/) | Fix missing values, labels, and duplicates | pandas |
| 5 | [Statistics & charts](05-statistics-charts/) | Two charts, and what they show | matplotlib |
| 6 | [Your first model](06-first-model/) | A prediction model tested against a simple baseline | scikit-learn |

New material is added here before each session.

## Get the materials

**First time:** make a copy of this repository on your computer (this is called *cloning*):

```bash
git clone https://github.com/valley-ai-club/workshops.git
```

**Every session after that:** get the newest lessons:

```bash
cd workshops
git pull
```

No Git on your computer, or using a school Chromebook? You can still follow along:

- **Read in the browser.** Every lesson is a page on this site. Click a session above.
- **GitHub Codespaces.** A coding environment in your browser with Git already set up.
  Session 1 shows how to open one.
- **Google Colab.** From session 3, notebooks open in Colab with one click.

## One rule: keep your work in your own repositories

Treat this repository as **read-only**. Don't edit files inside your `workshops` folder:
if you do, `git pull` can get stuck next week.

When an exercise asks you to change a file, **copy it into your own repository first**
(you'll make your first one in session 1). Your own repositories are where your work
lives, and they become your portfolio.

## Getting help

- **During a workshop:** raise your hand, or ask a mentor in office hours.
  If you're stuck for more than 5 minutes, ask.
- **Found a mistake or something unclear?** [Open an issue](https://github.com/valley-ai-club/workshops/issues/new)
  and tell us which page and what went wrong.
- **Using AI tools:** ChatGPT and similar tools are fine for explaining code and errors.
  Check what they tell you against your own results, and don't hand in code you don't understand.

## Staying safe online

Your GitHub profile and your website are **public**. Anyone can see them.

- Use your first name or a nickname.
- Never post your address, phone number, school schedule, or photos you wouldn't want strangers to see.
- Never share your password, including with instructors or mentors.
- GitHub accounts are for people **13 and older**. If you're 12, tell an instructor and
  you can pair up with a mentor.

## For instructors

Each session lives in its own numbered folder with a `README.md` lesson page.
Keep datasets small (a few MB at most) and link to large ones instead of committing them.
Students should only ever need `git clone` once and `git pull` after that, so avoid
renaming or moving files students have already copied.

---

The Valley AI Club is an independent community club and not an official UCLA program.

# Tonight's Git and Portfolio Build

## Finish line

By the end of tonight, aim to have:

- a GitHub account
- GitHub Desktop installed
- this folder saved as a Git repository
- your first commit completed
- the repository published
- GitHub Pages enabled
- a live portfolio URL

## Five Git words

**Repository:** the project folder Git tracks.

**Commit:** a labeled snapshot of the project.

**Push:** send local commits to GitHub.

**Pull:** bring newer GitHub changes onto your computer.

**Branch:** a separate line of development for safe experimentation.

That is enough vocabulary for night one.

## Recommended beginner path: GitHub Desktop

1. Create a GitHub account with a professional username.
2. Install GitHub Desktop and sign in.
3. Open this portfolio folder.
4. Choose **Create a Repository** if prompted.
5. For a personal website, name the repository exactly `YOUR_USERNAME.github.io`.
6. Use this description: `Mechanical engineering portfolio focused on systems integration, test engineering, and defense technology.`
7. Enter the commit message `Create initial engineering portfolio`.
8. Click **Commit to main**.
9. Click **Publish repository** and keep it public.

## Publish with GitHub Pages

1. Open the repository on GitHub.
2. Select **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save.

Your eventual URL will be:

```text
https://YOUR_USERNAME.github.io
```

## Make a second commit

Open `index.html` in VS Code or another editor. Replace `YOUR_USERNAME` with your username, save, and commit:

```text
Add GitHub profile link
```

## Core command-line reference

You do not need these commands tonight if you use GitHub Desktop:

```bash
git status
git add .
git commit -m "Describe the change"
git push
```

## Portfolio rules

- Do not publish proprietary company data.
- Do not exaggerate your technical ownership.
- Show requirements, decisions, tests, and results.
- Include failures and redesigns when they demonstrate engineering judgment.
- Favor four polished projects over twenty weak repositories.

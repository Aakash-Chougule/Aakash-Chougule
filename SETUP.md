# Upload Instructions

Upload this whole structure to your `Aakash-Chougule/Aakash-Chougule` repository:

```text
README.md
assets/
  hero.svg
  terminal.svg
  divider.svg
  architecture.svg
  skillflow.svg
  workflow.svg
  section-about.svg
  section-stack.svg
  section-projects.svg
  section-architecture.svg
  section-workflow.svg
  section-connect.svg
.github/
  workflows/
    snake.yml
```

## Important
Do NOT paste Markdown code blocks inside HTML tables. This package avoids that problem.

## Easiest way with GitHub website
1. Replace `README.md`.
2. Create each file under `assets/...` and paste its contents.
3. Create `.github/workflows/snake.yml`.
4. Commit changes.
5. Refresh your profile.

## Easiest way with Git
Copy all files into your local profile repository, then run:

```bash
git add .
git commit -m "Upgrade GitHub profile design"
git push origin main
```

## Enable contribution snake
After pushing `snake.yml`:
1. Open **Actions**
2. Open **Generate Contribution Snake**
3. Click **Run workflow**
4. Wait for success
5. Uncomment the `<picture>...</picture>` block in README

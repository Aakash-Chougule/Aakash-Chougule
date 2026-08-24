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


## Contribution animation — final setup

This version no longer needs an `output` branch.

The README always points to:

- `assets/github-snake.svg`
- `assets/github-snake-dark.svg`

The ZIP includes safe animated placeholders so the profile never shows a broken image.

After uploading everything:

1. Open repository **Settings → Actions → General**.
2. Under **Workflow permissions**, select **Read and write permissions**.
3. Open the **Actions** tab.
4. Run **Update Contribution Snake**.
5. The workflow will automatically overwrite the placeholder SVGs with your real contribution snake and commit them to `main`.
6. From then on, the scheduled workflow refreshes them daily.

No README editing is required after the workflow succeeds.

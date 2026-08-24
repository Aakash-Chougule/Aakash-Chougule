# Premium GitHub Profile — Setup

This package is designed for:

`https://github.com/Aakash-Chougule/Aakash-Chougule`

## Repository structure

```text
Aakash-Chougule/
├── README.md
├── assets/
│   ├── hero.svg
│   ├── terminal.svg
│   ├── architecture.svg
│   └── divider.svg
└── .github/
    └── workflows/
        └── snake.yml
```

## Important

Do **not** upload only `README.md`.

This profile uses local animated SVG assets, so upload the complete `assets` folder too.

## Fastest Git method

```bash
git add README.md assets .github/workflows/snake.yml
git commit -m "Redesign GitHub profile"
git push origin main
```

## Enable the contribution snake

1. Open the `Aakash-Chougule/Aakash-Chougule` repository.
2. Open **Actions**.
3. Select **Generate Contribution Snake**.
4. Click **Run workflow**.
5. Wait for it to finish successfully.
6. Edit `README.md`.
7. Find the **Contribution Animation** section.
8. Uncomment the `<picture>...</picture>` block.
9. Commit the README change.

If GitHub blocks the workflow from writing:
- Repository **Settings**
- **Actions**
- **General**
- Under **Workflow permissions**, choose **Read and write permissions**
- Save
- Run the workflow again

## Why this version should render better

The previous profile had two main problems:

1. Dynamic stats services could fail and leave broken images.
2. Markdown code blocks placed inside HTML layout elements could render as flattened text.

This version avoids both problems:
- the hero, terminal, divider and architecture are hosted in your own repository;
- animations are built into those SVG files;
- Mermaid diagrams are used only in normal Markdown;
- HTML tables are used only for short visual cards;
- no fragile public stats cards are required;
- the contribution snake is disabled until the generated image exists.

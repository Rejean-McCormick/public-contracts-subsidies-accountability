# Import the GitHub Wiki

The main GitHub repository and GitHub Wiki are separate Git targets.

1. Create or open the repository `public-contracts-subsidies-accountability`.
2. Upload README.md, CONTRIBUTING.md, docs/ and data/ to the main repository.
3. Enable GitHub Wiki and create its first page if needed.
4. Clone the wiki Git repository and copy the **contents** of the archive's wiki/ folder into its root.

```bash
git clone https://github.com/OWNER/public-contracts-subsidies-accountability.wiki.git
cp -R /PATH/TO/ARCHIVE/wiki/. public-contracts-subsidies-accountability.wiki/
cd public-contracts-subsidies-accountability.wiki
git add .
git commit -m "Publish English investigative wiki"
git push
```

Replace OWNER and local paths with real values. Home.md, _Sidebar.md and _Footer.md must be in the wiki root.

**Generating this ZIP does not publish anything to GitHub.**

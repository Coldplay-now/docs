# apikey Docs (Mintlify)

This repository is the standalone documentation source for `apikey`.

## Repository role

- Product website repo: `apikey-website`
- Docs repo (this repo): tutorials, CLI guide, security, FAQ, release process

## Local preview

Use Node.js LTS (22 recommended), then run:

```bash
npm i
npx mintlify dev
```

Open `http://localhost:3000` to preview.

## Update workflow

```bash
git checkout -b docs/your-change
# edit .mdx and docs.json
git add .
git commit -m "docs: your change"
git push
```

Create a PR and merge after review. Mintlify deployment runs from `main`.

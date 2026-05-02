# Shark Attack

## Deploy to GitHub and Vercel

1. Create a GitHub repository for this folder.
2. Commit the game files.
3. Push to your GitHub repository.
4. Connect the repository in Vercel and deploy.

Run from PowerShell in this folder:

```bash
git add .
git commit -m "Add Shark Attack web game"
git branch -M main
git remote add origin https://github.com/<your-github-user>/<your-repo>.git
git push -u origin main
```

Then in Vercel:

1. Click New Project.
2. Import your GitHub repository.
3. Use default settings.
4. Deploy.

The deployment route is set to load `shark-attack.html` at `/`.

## Files

- `shark-attack.html` game entry file
- `vercel.json` rewrites root to `shark-attack.html`

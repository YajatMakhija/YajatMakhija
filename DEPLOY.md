# GitHub profile README setup

This package is designed for the special GitHub profile repository:

`YajatMakhija/YajatMakhija`

1. Create a public GitHub repository named `YajatMakhija` in your account.
2. Upload the contents of this folder to the root of that repository, including `assets/` and `README.md`.
3. GitHub will automatically show the README on your profile at https://github.com/YajatMakhija.
4. The repo also includes the existing optional `index.html` portfolio; to publish it, enable GitHub Pages via **Settings > Pages > Source: GitHub Actions**.

## If using GitHub CLI

```bash
gh auth login
gh repo create YajatMakhija/YajatMakhija --public --source=. --remote=origin --push
```

Use `git add . && git commit -m "Upgrade cinematic profile" && git push` after changes, if the repository already exists.

The GIF and image assets use relative paths, which GitHub supports inside profile READMEs. A GitHub README cannot directly execute JavaScript, advanced web animation libraries, or embedded autoplay videos. The companion GitHub Pages site can.

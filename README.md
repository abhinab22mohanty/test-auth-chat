# test-auth-chat
Repository to host auth chat public key via GitHub Pages

## Setup

This repository is configured to host a public key via GitHub Pages.

### Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to use (typically `main` or `copilot/fix-b345097e-3f34-4bb1-8401-c218da29cd70`)
4. Click "Save"

Once enabled, your public key will be accessible at:
```
https://abhinab22mohanty.github.io/test-auth-chat/public_key.pub
```

### Adding Your Public Key

Replace the placeholder content in `public_key.pub` with your actual public key.

### Files

- `index.md` - Landing page for the GitHub Pages site
- `public_key.pub` - Your public key file
- `.nojekyll` - Disables Jekyll processing for faster serving

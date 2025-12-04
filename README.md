# IGHAStar GitHub Pages

This repository contains the GitHub Pages website for IGHAStar.

## Setup

1. Push this repository to GitHub as `ighastar.github.io` (or `yourusername.github.io/ighastar` if using a project site)
2. Enable GitHub Pages in the repository settings
3. The site will be available at `https://ighastar.github.io`

## Cloning with Git LFS

This repository uses [Git LFS](https://git-lfs.github.com/) to store large video files. When cloning on a new system, you have two options:

**Option 1: Use `git lfs clone` (Recommended)**
```bash
git lfs clone https://github.com/sidtalia/ighastar.github.io.git
```

**Option 2: Regular clone + LFS pull**
```bash
git clone https://github.com/sidtalia/ighastar.github.io.git
cd ighastar.github.io
git lfs pull
```

**Note:** Make sure Git LFS is installed on your system:
```bash
# Ubuntu/Debian
sudo apt install git-lfs

# macOS
brew install git-lfs

# Then initialize (one-time setup)
git lfs install
```

## Structure

```
ighastar.github.io/
├── index.html          # Main page
├── Content/            # Images and media files
├── static/
│   └── css/
│       └── index.css   # Custom styles
└── .nojekyll          # Disable Jekyll processing
```

## Content

The `Content/` folder contains:
- `IGHAStar_main_fig.png` - Main figure
- `ighastar_sim.gif` - Simulation demo
- `ighastar_real.gif` - Real-world demo
- `standalone/` - Example result images

## Customization

Edit `index.html` to customize the content, and `static/css/index.css` to modify the styling.


<div align="center">

```
██████╗  ██████╗  ██████╗ ██╗  ██╗███╗   ███╗ █████╗ ██████╗ ██╗  ██╗███████╗
██╔══██╗██╔═══██╗██╔═══██╗██║ ██╔╝████╗ ████║██╔══██╗██╔══██╗██║ ██╔╝██╔════╝
██████╔╝██║   ██║██║   ██║█████╔╝ ██╔████╔██║███████║██████╔╝█████╔╝ ███████╗
██╔══██╗██║   ██║██║   ██║██╔═██╗ ██║╚██╔╝██║██╔══██║██╔══██╗██╔═██╗ ╚════██║
██████╔╝╚██████╔╝╚██████╔╝██║  ██╗██║ ╚═╝ ██║██║  ██║██║  ██║██║  ██╗███████║
╚═════╝  ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
```

**Personal bookmark collection — portable, minimal, always available.**

![YAML](https://img.shields.io/badge/YAML-bookmarks-red?style=flat-square&logo=yaml)
![HTML](https://img.shields.io/badge/HTML-browser--import-orange?style=flat-square&logo=html5)

</div>

---

## What is this?

A single source of truth for all my bookmarks. Two formats in one place:

| File | Purpose |
|---|---|
| `src/bookmarks.yaml` | Used by my [startpage](https://github.com/badjavii/startpage) for live shortcut search |
| `src/bookmarks.html` | Standard Netscape format — importable into any browser |

---

## Structure

```
badjavii-bookmarks/
└── src/
    ├── bookmarks.yaml   ← startpage shortcuts
    └── bookmarks.html   ← browser import
```

---

## How to use

### Import into your browser

1. Download `src/bookmarks.html`
2. Open your browser's bookmark manager
3. Look for **Import bookmarks**
4. Select the HTML file

> Works on Chrome, Brave, Firefox, Edge, and pretty much any browser.

### Use with a startpage

If you're running a startpage that fetches shortcuts from a remote YAML, point it to the raw URL:

```
https://raw.githubusercontent.com/badjavii/badjavii-bookmarks/refs/heads/main/src/bookmarks.yaml
```

---

## Categories

| Category | Description |
|---|---|
| Dev | GitHub, docs, references, tools |
| Linux & OS | ArchWiki, FreeBSD, LFS, Linux resources |
| Academia | UCV portals, research tools, LaTeX utilities |
| Design | Color tools, icon packs, wallpapers |
| AI | Claude, DeepSeek, Gemini |
| Google | Gmail, Drive, Calendar, Photos |
| Proton | Mail, Pass, Drive |
| Media | YouTube, Spotify, anime, ROMs |
| Social | Reddit, WhatsApp, Telegram |
| Tools | Notion, VirusTotal, misc utilities |

---

Proudly designed and maintained by Badjavii.

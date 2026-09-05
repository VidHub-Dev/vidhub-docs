# VidHub Documentation (`vidhub-docs`)

> The official user documentation, onboarding guides, and workflow tutorials for the VidHub ecosystem.

---

## What is VidHub?

**VidHub is the definitive version control and collaboration platform designed specifically for video editors.** 

In modern post-production, creative teams deal with massive project files, complex multi-track timelines, and heavy raw camera media. Traditional collaboration approaches force editors to manually duplicate project files (e.g., `Project_Final_v2_really_final.drp`), email XMLs, or risk overwrite disasters on shared drives. 

VidHub replaces that chaos with structured, non-destructive version control directly inside your editing suite.

---

## How is VidHub Different from Blackmagic Cloud?

Blackmagic Cloud revolutionized real-time collaborative editing by allowing multiple editors to work in the same project simultaneously. However, **real-time collaboration is not version control**:

| Capability | Blackmagic Cloud | VidHub |
| :--- | :---: | :---: |
| **Real-time multi-user timeline presence** | ✅ Yes | 🔄 Planned |
| **Complete commit history & timeline snapshots** | ❌ No | ✅ Yes |
| **Isolated branching for alternate cuts / color passes** | ❌ No | ✅ Yes |
| **Non-destructive rollback & stashing** | ❌ No | ✅ Yes |
| **Semantic timeline merge conflict resolution** | ❌ No | ✅ Yes (Manual & AI) |
| **Template marketplace integration** | ❌ No | ✅ Yes |
| **Zero-egress footage sync with chunked caching** | ❌ No | ✅ Yes |

With VidHub, you never have to fear making experimental edits. You can create a new branch for a director’s cut, experiment freely, and cleanly merge your changes back into the main timeline when approved.

---

## Core Workflow Concepts

VidHub uses a custom timeline versioning protocol (the `vid` protocol) engineered to understand video timelines rather than plain text lines:

- **Save Version (`vid add`):** Captures the current state of your cuts, tracks, and media pool bins locally.
- **Commit (`vid commit`):** Records a permanent snapshot in your project's local history with an explanatory log message.
- **Branching (`New Branch` / `Switch Branch`):** Creates parallel working paths (e.g., `main`, `director-cut`, `vfx-pass`).
- **Push (`vid push`):** Encrypts and synchronizes your timeline changes and media assets to the cloud.
- **Stash (`vid stash`):** Safely discards local experimentation and reverts your timeline to the last clean commit state.
- **Merge & AI Resolve:** Merges two branches together. When timeline cuts overlap, our AI engine resolves track collisions intelligently with a one-click rollback safety net.

---

## Getting Started & Plugin Setup

VidHub integrates directly into **DaVinci Resolve** via an interactive desktop wizard and workflow plugin.

### Prerequisites
- DaVinci Resolve 18.5+ (Free or Studio edition)
- Python 3.10 or higher
- A free account on our website []()

### Installation Walkthrough
1. **Download the Installer:** Grab the latest installer from the releases page of [vid-davinci](https://github.com/VidHub-Dev/vid-davinci).
2. **Run the Setup Wizard:** Launch the executable installer. It will automatically detect your DaVinci Resolve scripts and workflow integrations directory.
3. **Connect Your Account:** Log in with your VidHub account credentials during setup.
4. **Open DaVinci Resolve:** Inside Resolve, navigate to `Workspace > Scripts > VidHub` to launch the dockable VidHub toolbar.

*(Full visual step-by-step guides and video walkthroughs coming soon.)*

---

## About This Repository

This repository houses the source markdown, guides, and documentation portal for the VidHub platform.

### Local Documentation Development
The documentation site is currently in active development.

- **Status:** Coming soon.
- Instructions for running the documentation site locally with static site generators will be provided here upon release.

---

## License

All Rights Reserved — see [LICENSE](LICENSE).

---

## Contact & Community

- **Website:** []()
- **General Inquiries & Support:** [vaibhavsoni280506@gmail.com](mailto:vaibhavsoni280506@gmail.com)
- **GitHub Organization:** [github.com/VidHub-Dev](https://github.com/VidHub-Dev)

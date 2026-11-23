# The rootkid/code project map

> **Portfolio context — not release documentation.** This page distinguishes what visitors can actually inspect from private experiments. A polished presentation is not a substitute for QA.

## Publicly accessible

### [Showcase Studio — Release Hub](https://github.com/rootkid-code/showcase-studio-releases)

**Theme:** Make complicated n8n automation flows understandable for demos, teaching and review.

- **Why:** Workflow logic can be hard to explain outside the editor.
- **Approach:** Local-first, read-only presentation and explicit sharing/review decisions.
- **Project areas:** n8n/JSON import, seven presentation styles, workflow visualization, structured descriptions and privacy-aware offline exports. **Make and Zapier are currently visual looks only; their import adapters are planned.**
- **Public status:** **[`v1.0.0-beta.4`](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) is publicly available as a pre-release Windows ZIP**; it is not a stable or independently verified Windows/security production release.
- **What not to assume:** A release-ready Windows build, commercial offering, security certification or production support.

### [Tresor / Beta Lab](https://github.com/rootkid-code/tresor-releases)

**Theme:** Explore local desktop development and release processes with Tauri, Rust, React and TypeScript.

- **Why:** Building a local application involves more than designing its screens.
- **Approach:** Experimental desktop builds, test-oriented release documentation and safety caveats.
- **Public status:** Experimental beta materials and releases only.
- **Explicit safety boundary:** **Disposable, non-sensitive test data only.** Not for real records, passwords, personal documents or important files. Not an audited security product.

## Private explorations

These names represent areas explored in private work. The repositories are **not accessible publicly**, and this page does not claim that they are deployed, production-ready or ready for download.

| Project | Question explored | Main disciplines |
|:--|:--|:--|
| Kettenwerk | How do bicycle inquiries flow into workable service processes? | Product design, workflow automation, role-based operations |
| KI-Atlas | How can AI concepts be explored as a connected knowledge network? | Educational UX, content models, interactive visualization |
| SYNTHESIS | How can cinematic 3D storytelling move from Blender into the browser? | Art direction, WebGL, performance, deterministic scenes |
| Career Workspace | How can AI help prepare applications without inventing experience? | Structured data, evidence review, safe drafting |

## Public release checklist

Before publishing another project or case study:

1. **Rights:** Confirm ownership and allowed use of code, fonts, images and educational content.
2. **Privacy:** Remove real users, customer details, family information, tokens, credentials and logs from the material.
3. **History:** Check **Git history**, not just current files; old commits and metadata can disclose email addresses and secrets.
4. **Accuracy:** Separate implemented, tested and planned features. Screenshots must come from attributable builds.
5. **Architecture:** Present useful system boundaries without exposing secrets or administrative tooling.
6. **Licenses:** Explicitly decide whether code is source-available, open-source licensed or documentation-only.
7. **Experience:** Offer a comprehensible README and a credible way to understand or try the result.
8. **Release:** Publish an installer or download link only when the corresponding asset really exists and its QA evidence is recorded.

**Commercial scope:** Free/community usefulness and quality first. Sales, pricing and Pro commercialization are **on hold**.

[← Back to English profile](README.en.md)

# Rumah Warisan Maya — active web prototype

This folder is the planned browser-first traditional Malay house experience. The repository's original Galeri Warisan Maya remains intact on `main`; changes are developed on `feature/rumah-warisan-maya` and reviewed before merging.

## Experience direction
- A believable, lightweight traditional Malay house: serambi, rumah ibu, dapur.
- Clear visitor journey and next-stop guidance.
- Exhibit introductions appear automatically when visitors approach; no repetitive E-key prompts.
- Deeper cultural descriptions and optional questions.
- Interactive batik, wau, songket, keris, and kuih demonstrations.
- Optimized, properly licensed GLB/glTF heritage artifacts where available; procedural geometry remains a placeholder.
- Browser desktop first, WebXR VR second. No Blender requirement for development.

## Workflow
1. Work on a feature branch.
2. Review the pull request before merging to `main`.
3. Preview public branches via GitHub + StackBlitz, where supported, or serve the static web app with a simple server.
4. Keep the old exhibit implementation available while replacing modules progressively.

## Immediate next step
Integrate the existing Rumah Warisan Maya v0.3 prototype into this repository as a separate `rumah-warisan/` application, then test its movement, navigation, exhibit interactions, and performance before promoting it to the main entry point.

**Note:** This document is a development setup, not the v0.3 source-code migration. The latter still needs its own commit.

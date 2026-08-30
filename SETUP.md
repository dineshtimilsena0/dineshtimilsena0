# Setup

1. Put the contents of this folder into the repository:
   `https://github.com/dineshtimilsena0/dineshtimilsena0`
2. Commit `README.md`, `assets/`, and `.github/workflows/profile-visuals.yml`.
3. In GitHub: Settings → Actions → General → Workflow permissions → allow read and write permissions.
4. Open Actions → Generate Profile Visuals → Run workflow.
5. The workflow publishes generated contribution SVGs to the `output` branch.
6. The README already points to those generated files.

The local SVG assets are animated with native SVG `<animate>` elements, so they require no JavaScript.

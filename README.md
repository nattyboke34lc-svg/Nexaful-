# FRAMEFLOW

A browser-based screenplay-to-film production workspace. This first release provides screenplay intake, scene extraction, character continuity notes, storyboard generation and approval, and a shot-production tracker.

## Run locally
Open `index.html` in a modern browser, or serve this directory with any static web server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Current capabilities
- Import TXT and Markdown screenplays. DOCX/PDF can be pasted as text in this first release.
- Extract scene headings, character cues and dialogue using screenplay conventions.
- Create editable character continuity cards.
- Generate an editable shot list from extracted scenes.
- Approve shots individually before production.
- Track shot status and attach locally selected preview clips.
- Export/import a project JSON backup.

## Privacy
Project data is stored in this browser's local storage on this device. It is not uploaded to this public repository or to a FRAMEFLOW server. Do not use a shared/public device for confidential screenplays. Clearing browser data can erase local projects, so export backups.

## Important limitations
This is a functional local-first MVP, not a deployed multi-user service. It does not yet call a video-generation provider or render a finished MP4. Provider integrations, secure account authentication, cloud storage, server-side document conversion, and automated final assembly are separate engineering milestones. Never put API keys in browser code.

## Deploy
The repository can be connected to a static hosting provider. For a private hosted workspace, enable host-level access protection before uploading any private project material. The source repository is public by design; screenplay content and credentials must stay out of Git.

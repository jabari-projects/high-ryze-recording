# Planned architecture

High Ryze Recording is planned as a desktop-focused gameplay recording and highlight-creation platform. The repository separates the future user-facing application under `app/` from processing and integration responsibilities under `backend/`, keeping the UI, video workflow, and AI-assisted analysis independently evolvable.

The planned workflow is intentionally simple: a user records or imports gameplay footage, the project analyzes that footage to identify candidate moments, the user refines selected highlights with editing tools, and the result is exported for short-form platforms. The exact frontend, backend, AI, storage, and processing implementations remain undecided; the existing project direction names React or Electron, Python or Node, local and cloud AI, FFmpeg, and local or optional cloud storage as options rather than fixed decisions.

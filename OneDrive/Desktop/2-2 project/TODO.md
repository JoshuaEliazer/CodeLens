# TODO - CodeLens (MERN Student Code Analysis)

- [x] Create project structure (client, server, shared docs)
- [x] Add backend (Node/Express) with MongoDB models + JWT auth + roles (student/instructor)
- [x] Add submission endpoints (paste + upload), store code + language + metadata
- [x] Implement analysis pipeline:
  - [x] Static metrics: LOC, complexity estimate, style counts
  - [x] Duplication-ish similarity via code fingerprint / token n-grams
  - [x] ESLint results for JS/TS
- [x] Add safe sandbox tests runner (optional test harness) for JS/TS (and graceful for Python)
- [x] Add frontend (React + Vite): auth screens, submit code UI, analysis dashboard
- [x] Add instructor panel: view submissions + compare similarity
- [x] Add README with local setup + resume-friendly feature list
- [x] Add basic seed/sample data script
- [x] Run and verify: lint/build/start for both client and server
- [x] (Optional) Add Dockerfile/docker-compose for resume polish

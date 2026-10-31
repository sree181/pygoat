# PyGoat: notes for coding agents

PyGoat is an intentionally vulnerable Django app used for security training.
Many labs are insecure on purpose. Do not "fix" lab code unless asked.

- App code: `introduction/` (views in `introduction/views.py`, routes in `introduction/urls.py`).
- Settings: `pygoat/settings.py`. Dependencies: `requirements.txt`.
- CI: `.github/workflows/`. Change CI only when the task says so.
- Local secrets live in `.env` (never committed).
- Keep changes small and in the files the task names.

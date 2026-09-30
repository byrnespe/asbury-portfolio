# PermitPilot

**What it is.** Automation for New Jersey UCC permit packets. Parses and auto-fills
government forms, decodes equipment serial numbers into permits, and generates
ReportLab PDF permit packets. Ships as Flask backend + Alembic migrations + Docker +
native desktop (pywebview) + iOS workspace.

**Stack.** Python, Flask, SQLAlchemy/Alembic migrations, Docker, ReportLab PDF,
pywebview desktop, Expo/iOS, CI/CD.

**What it demonstrates.**
- Domain-specific document automation (govtech/regtech).
- Full-stack + schema migrations + Docker + native desktop + mobile.
- Serial-number decoding and form mapping/verification logic.

**Status.** Live pilot (not yet paying).

**Source.** `~/projects/permitpilot/` (backend), `~/projects/permitpilot-desktop/`, `~/projects/permitpilot-ios/`.

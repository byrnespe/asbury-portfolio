# Asbury CRM

**What it is.** An installable CRM dashboard: a FastAPI app packaged as a
checksummed installable payload, with backup/doctor/launch tooling and a
Plaud → CRM sync integration.

**Stack.** Python, FastAPI, `install.py`/`install.sh`, `backup.sh`/`doctor.sh`/`launch.sh`,
SHA256SUMS manifest, integrations.

**What it demonstrates.**
- Product packaging and shipping discipline (checksummed, installable payload).
- Ops/self-check tooling (backup, doctor).
- Data-source integration (Plaud sync).

**Status.** Built; internal/operational tooling.

**Source.** `~/projects/asbury-crm/`.

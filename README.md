# Medicaid Navigator in a Box  (Powered by IDIS/QuantaIQ)

A lightweight, open-source toolkit to help individuals and communities stay enrolled in Medicaid — especially as new recertification requirements roll out nationwide.

Built on the IDIS + QuantaIQ architecture, this module is optimized for deployment in:
- Libraries
- Tribal Health Organizations (THOs)
- Behavioral Health Centers
- Shelters and rural hubs

## 🔧 Core Features

- Document intake + classification
- Medicaid eligibility logic engine (state-specific)
- Auto-filled renewal form packet generation
- Local deployment via Docker (no always-on internet required)
- Optional telemetry for deadline tracking, gap detection, and analytics

## 🧱 Repo Structure

| Folder         | Purpose                                  |
|----------------|------------------------------------------|
| `docker/`      | Docker build and deploy scripts          |
| `forms/`       | Medicaid form templates & output logic   |
| `intake/`      | User intake form structure & logic       |
| `logic/`       | Eligibility trees, deadline models       |
| `ui-mockups/`  | Screenshots or design files              |
| `docs/`        | Grant materials, pilot guides, research  |

## 📦 Deployment Status

> This is a work in progress. Core components are built; this repo will track the Medicaid-specific module buildout.

## 🔓 License

MIT License (see `LICENSE` file)

---

_Questions or collaboration inquiries: contact Tim Scheffel, DO._

# Helix Core — Release Binaries

Public download mirror for **Helix Core**, an AI-powered drug discovery desktop suite by [Amr Mohamed](https://github.com/AmrMohamed).

This repository hosts only the compiled Windows release artifacts. The source code lives in a private repository and is not distributed here.

## Latest release

Download the most recent build from the [Releases page →](../../releases/latest)

| Asset | Description |
| --- | --- |
| `HelixCore-<version>-Final-portable.exe` | Portable Windows executable, no installer |
| `HelixCore-<version>-Final-portable.zip` | Same build, ZIP archive |

## What is Helix Core?

End-to-end virtual screening on the desktop:

- PDB fetch + UniProt annotation
- Pocket detection and grid-box calculation
- Batch 3D ligand generation, energy minimization, format conversion
- AutoDock Vina docking with auto-grid and config profiles
- ML-based affinity rescoring (Oracle AI)
- ADMET, interaction profiling, chemical clustering, analog generation
- Project snapshots and compound watchlist

18 modules, 42 backend endpoints, single portable EXE. Bundles RDKit, OpenBabel, AutoDock Vina, FastAPI, React, Electron.

## Installation

1. Download `HelixCore-<version>-Final-portable.exe` from [Releases](../../releases/latest)
2. Double-click. No installer, no admin rights required.
3. Activate with the license key emailed to you.

## License

Helix Core is proprietary software. Each license is bound to one machine.

To request an academic or research license, fill out the [request form on the landing page](https://your-landing-page-url.com#license) or email **AAlhfnawy@nu.edu.eg**.

## System requirements

- Windows 10 / 11 (x64)
- 8 GB RAM minimum, 16 GB recommended for batch docking
- ~2 GB free disk
- Internet only required for activation and external lookups (PDB, ChEMBL, PubChem)

## Verifying a download

Each release includes the SHA-256 checksum of the EXE in the release notes. Verify with:

```powershell
Get-FileHash .\HelixCore-1.0.0-Final-portable.exe -Algorithm SHA256
```

Compare the output to the value in the release notes.

## Issues and bug reports

For technical issues, please email **AAlhfnawy@nu.edu.eg** or **amrmo211999@gmail.com**.

The issue tracker on this repository is not actively monitored — bug reports are tracked in the private development repository.

---

**Helix Core** © Amr Mohamed. All rights reserved.

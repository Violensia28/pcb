
# UPB v1.0 — Gerber CI Repo

**How to build Gerber v1.0 Final:**
1. Upload this ZIP as a repository to GitHub (Add file → Upload files → Commit).
2. Go to **Actions** → run **Export Gerbers (KiCad CLI v1.0)**.
3. Download **artifact**: `UPB_v1p0_Gerber_Final.zip` (contains RS-274X + Excellon Drill).

**Manufacturing settings (JLCPCB):**
- Layers: 2; FR-4 **2.0 mm**; **Cu 2 oz**; **HASL (leaded)**.
- Upload ZIP to JLCPCB → Quote Now → Verify layers in Online Gerber Viewer → Checkout.

**Note:** Nets are optional for manufacturing; KiCad CLI exports copper pads, drills, mask & silk from the PCB.

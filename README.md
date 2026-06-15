# OrCAD Capture TCL/TK Automation

A collection of **production-ready TCL/TK automation scripts** for OrCAD Capture schematic design workflows. These tools automate repetitive schematic tasks — developed over 6+ years of hands-on EDA engineering.

---

## 📦 Programs

### Panelling
| Program | Description |
|---|---|
| **Auto Panel** | Automated PCB panel creation with configurable array layout and spacing |
| **Panel Compare** | Compares panel configurations between two designs for consistency validation |

### DFM Checks
| Program | Description |
|---|---|
| **DFM Check** | Design for Manufacturing validation suite — checks component spacing, courtyard violations, and assembly constraints |
| **DFM Report** | Generates structured DFM check reports with pass/fail status per rule |

### Gerber Operations
| Program | Description |
|---|---|
| **Gerber Compare** | Layer-by-layer Gerber file comparison between two PCB revisions |
| **Gerber Export** | Automated Gerber file generation with standard layer naming |

### IPC Checks
| Program | Description |
|---|---|
| **IPC Check** | IPC-2221/2222 compliance validation for PCB design rules |
| **IPC Report** | Structured IPC compliance report generation |

---

## 🚀 Highlights

- **Gerber Compare** — Performs automated diff between Gerber revisions, flags layer-level differences, and generates a mismatch report. Eliminates manual visual inspection.
- **Auto Panel** — Configurable panelling automation with step-and-repeat logic, V-score line placement, and fiducial positioning.
- **DFM Check** — Rule-based validation covering 15+ DFM checks per IPC standards.

---

## 🛠️ Requirements

- CAM 350 (version 10.x or higher)
- Macro scripting enabled

---

## 📂 Usage

1. Open CAM 350
2. Go to **Utilities → Macros → Run Macro**
3. Select the `.scr` file
4. Configure parameters in the dialog and run

---

## 👤 Author

**Karthikeyan K** — EDA Automation Engineer  
[github.com/karthikeyankcse](https://github.com/karthikeyankcse)

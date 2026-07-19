# Open-Source 3D-Printed Medical Replacement Components

This repository serves as a centralized, open-source registry for 3D-printed medical device replacement components. It is designed to assist biomedical engineers and clinical technicians in sourcing, manufacturing, and validating critical spare parts for medical equipment—especially in resource-constrained environments or crisis zones where supply chains are disrupted.

Every component listed in this repository represents a localized engineering solution aimed at reducing clinical downtime and restoring life-saving diagnostic and therapeutic machinery to active service.

---

## 📂 Repository Structure

The repository is organized into independent, self-contained project directories. Each directory includes its respective parametric source files, manufacturing profiles, documentation, and specific validation parameters:

```text
.
├── 📁 infusion-pump-gear/              # Project 1: Syringe Pump Drivetrain Replacement
│   ├── 📁 design-files/                # FreeCAD (.FCStd)
│   ├── 📁 print-files/                 # Production-ready .stl and calibrated .3mf profiles
│   ├── 📁 docs-and-manuals/            # Equipment user/service manuals (PG-801D)
│   ├── 📁 media/                       # Inspection photographs and deployment videos
│   └── 📄 README.md                    # In-depth technical guide & validation workflow for the gear
│
├── 📁 cr-cassette-slide-latch/         # Project 2: Computed Radiography Cassette Repair
│   ├── 📁 design-files/                # FreeCAD (.FCStd) files
│   ├── 📁 print-files/                 # Standard mesh (.stl) and .3MF files
│   ├── 📁 docs-and-manuals/            # Technical reference material and user manuals
│   ├── 📁 media/                       # Fitment and operational reference media
│   └── 📄 README.md                    # 
│
└── 📄 README.md                        # This root registry overview documentation

# Makera-Z1-4th-Axis

This project repo aims to allow Makera Z1 owners to build and source their own parts in order to build a 4th axis on their own.

Repository folder structure added:

- BOM/
  - Place Bill of Materials files here (CSV, XLSX or similar). Example filename: `makera_z1_4th_axis_bom.csv`.

- STL files/
  - Place 3D model files (.stl) for printed parts here. Keep filenames descriptive and versioned, e.g. `jaw_plate_v1.stl`.

How to use
- Add BOM files to the `BOM/` directory. Include columns for part name, quantity, material, supplier/link, and notes.
- Add exported STL files to the `STL files/` directory. Prefer one part per STL file and include versioning in filenames.

Notes
- The repository currently includes placeholder files to ensure these directories are tracked by git. Replace the placeholders with your actual BOM and STL files.

If you'd like a different folder naming convention (for example `stl_files` instead of `STL files`) or additional subfolders (e.g., `source_models/`, `drawings/`), tell me and I can update the structure.
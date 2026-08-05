# Makera-Z1-4th-Axis

This project repo aims to allow Makera Z1 owners to build and source their own parts in order to build a 4th axis on their own.

Repository folder structure added:

- BOM/
  - Place Bill of Materials files here (CSV, XLSX or similar). Example filename: `makera_z1_4th_axis_bom.csv`.
  - From first picture and identification of the legacy build:
    - NEMA 17 x 1
    - 12T GT2 Pulley x 1
    - 60T GT2 pulley x1
    - Neodyme Magnet
    - Hall sensor x1
    - GT2 Belt (length to be validated) x1
    - Self Centering jaw chuck x1
   
- DYI version will include:
  - 10 mm H6 steel rod x1 (length to be validated)
  - 7000-2RS bearing (ideally AC P5) x2

- STL files/
  - Place 3D model files (.stl) for printed parts here. Keep filenames descriptive and versioned, e.g. `jaw_plate_v1.stl`.

How to use
- Add BOM files to the `BOM/` directory. Include columns for part name, quantity, material, supplier/link, and notes.
- Add exported STL files to the `STL files/` directory. Prefer one part per STL file and include versioning in filenames.

Notes
- The repository currently includes placeholder files to ensure these directories are tracked by git. Replace the placeholders with your actual BOM and STL files.

If you'd like a different folder naming convention (for example `stl_files` instead of `STL files`) or additional subfolders (e.g., `source_models/`, `drawings/`), tell me and I can update the structure.

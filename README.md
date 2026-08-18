
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/c9fecce6-0f04-4d9f-a1c8-18975ff3c880" />

# Makera-Z1-4th-Axis

This project repo aims to allow Makera Z1 owners to build and source their own parts in order to build a 4th axis on their own.

Repository folder structure added:

- BOM/
  - Place Bill of Materials files here (CSV, XLSX or similar). Example filename: `makera_z1_4th_axis_bom.csv`.
  - From first picture and identification of the legacy build:
    - NEMA 17 x 1
    - 12T GT2 Pulley x 1 12T 6mm x 5mm axis [source here](https://www.aliexpress.com/item/1005006217674592.html?spm=a2g0o.order_list.order_list_main.29.e4d35e5b72unb5)
    - 60T GT2 pulley x1 60T 6mm x 10mm axis [source here](https://www.aliexpress.com/item/1005005779406807.html?spm=a2g0o.order_list.order_list_main.11.e4d35e5b72unb5)
    - Neodyme Magnet
    - Hall sensor x1
    - GT2 Belt (length 176mm) x1 [source here](https://www.aliexpress.com/item/1005007811742786.html?spm=a2g0o.order_list.order_list_main.23.e4d35e5b72unb5)
    - Self Centering jaw chuck x1 with the 10mm rod adapter [source here](https://www.aliexpress.com/item/1005009437663583.html?spm=a2g0o.order_list.order_list_main.35.e4d35e5b72unb5)
   
- DYI version will include:
  - 10 mm H6 steel rod x1 (length to be validated) [source here](https://www.aliexpress.com/item/1005001628031225.html?spm=a2g0o.order_list.order_list_main.5.e4d35e5b72unb5) **Danger H8/h9 not h6**
  - 7000-2RS bearing (ideally AC P5) x2 [source here](https://www.aliexpress.com/item/1005012423323576.html?spm=a2g0o.order_list.order_list_main.17.e4d35e5b72unb5)

- STL files/
  - Place 3D model files (.stl) for printed parts here. Keep filenames descriptive and versioned, e.g. `jaw_plate_v1.stl`.

How to use
- Add BOM files to the `BOM/` directory. Include columns for part name, quantity, material, supplier/link, and notes.
- Add exported STL files to the `STL files/` directory. Prefer one part per STL file and include versioning in filenames.

Notes
- The repository currently includes placeholder files to ensure these directories are tracked by git. Replace the placeholders with your actual BOM and STL files.

If you'd like a different folder naming convention (for example `stl_files` instead of `STL files`) or additional subfolders (e.g., `source_models/`, `drawings/`), tell me and I can update the structure.

Follow-up: 
Assembly is ongoing. The first backplate version seems to be fine:
<img width="949" height="717" alt="image" src="https://github.com/user-attachments/assets/35055728-1935-487b-b824-cc5adddebfd9" />

**Summary of the costs (in CAD):**
- NEMA 17  0$ (in stock)
- 12T GT2 Pulley 4.89$
- 60T GT2 pulley 7.88$
- Neodyme Magnet 0$ (in stock)
- Hall sensor TBC
- GT2 Belt 2.95
- Self Centering jaw chuck 35.65$
- 10 mm H6 steel rod 12.18
- 7000-2RS bearing 18.16

**Grand Total = 81.71** 



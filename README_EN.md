# Ant Barrier Kettle Stand v1.8 — Six Legs, 10 mm Inverted Underside

Open `preview.html` for the offline English viewer. The stand has a Ø180 mm round platform, 50 mm above the table. The lower tray and **six legs** print as one piece; the crown prints separately.

## Geometry

Six legs sit evenly on a **Ø126 mm center circle**, each Ø32 mm at its upper neck and Ø14 mm at the foot. The main taper remains 16.1° from vertical, with 0.8 mm walls and a 0.8 mm root blend. Maximum root radius is **79.8 mm**, inset 10 mm from v1.7. The complete base remains inside Ø180 mm, without projecting tabs.

The outer **10 mm of the underside is clear around the full perimeter**. Legs, beams and the seating rib stay inside radius 80 mm, restoring an inverted traversal from the legs to the tray edge before the side channel. Changing only the leg count would not restore this surface: v1.7's minimum root-to-edge gap was just 0.2 mm.

The **1.2 mm closed lower panel** and six radial ribs, **3.2 mm wide and 8 mm deep below the channel floor**, remain. Buried beam ends join a continuous seating rib at radii **77–80 mm**, extending **3.2 mm below the floor**. It directly supports the existing crown seat after insetting the legs and stays inward of the clear underside band. Foot cavities retain 45° roofs and Ø4 mm vents. Do not perforate the closed panel.

Minimum support radius is **61.2 mm**, 9.0% above the physically printed v1.5 four-leg base's 56.1 mm. It is 17.4% below v1.7's 74.0 mm because the feet move inward. Six legs distribute support more evenly by direction, but neither leg count nor these geometry ratios establish a physical tipping improvement. Check all six feet on a flat table after printing.

The crown STL is byte-for-byte unchanged from v1.6. The original seating ring (radius **79.2–80 mm**), locating profile and 0.2 mm radial clearance are retained. CAD interference and mating-surface checks confirm compatibility with the old crown. The new revision has not been physically fit-tested.

The annular channel remains 10 mm high, 10 mm deep at its floor and 6 mm deep beneath the crown ledge. The inner wall flares outward 4 mm at 21.8°. Two integral 2 mm rims surround a 7.4 mm-wide liquid floor, 1.2 mm thick; 1 mm liquid depth holds about 3.85 mL. The viewer route follows the tray underside, outer rim, sloped wall and upper inverted ledge. It illustrates a possible traversal, not ant behaviour.

## Two parts, two print plates

Use **A1 / 0.4 mm nozzle / 0.20 mm Standard / actual PLA and plate / supports OFF**. Preserve the supplied STL orientations:

| File | Bed-facing surface | Bounding box |
| --- | --- | --- |
| `models/01_upper_crown_print.stl` | Kettle contact face | 180 × 180 × 14 mm |
| `models/02_lower_base_integrated_print.stl` | Closed panel and rim tops; legs UP | 180 × 180 × 38 mm |

The new base was resliced with Generic PLA and support generation disabled. The unchanged crown and sample reuse v1.6 slicing records after exact STL SHA256 matching; no new upper slice is claimed. Choose the actual spool formulation and plate. Stock reference records retain bed-temperature and timelapse notices; successful support checking does not qualify a print job.

The base roots grow from the panel or channel floor. A **6.6 mm channel bridge** remains and needs a physical surface-quality check. Inspect approximately six continuous panel layers at 0.2 mm, complete channel surfaces, leg-wall paths and an uninterrupted crown seating ring. Do not use vase mode or discard thin features. A slicer wall-loop setting cannot thicken a modeled shell.

The optional `models/03_crown_surface_test_optional.stl` is a ~45° crown sector. Generic PLA standard slicing estimates **3.8 g**. Print it contact face down to check roof and final seating-arc formation before repeating a whole crown. It is a diagnostic sample, not a third assembly component. The central crown lattice intentionally remains open; missing designed solid surfaces are print defects.

`models/ant_kettle_base_geometry.3mf` contains the two main objects in mm, without printer, filament, process or G-code. Assign one object to each of two plates in Bambu Studio. `assembly_reference_DO_NOT_PRINT.stl` is only an assembled reference.

The user reported that water treatment of the plate resolved previous first-layer lifting. No sacrificial peel-away film is added. After cooling, remove the plate, clean and dry fully before refitting; do not pour water onto a powered heatbed. See [Bambu's official Textured PEI plate care](https://us.store.bambulab.com/collections/accessories-for-a1-mini/products/bambu-textured-pei-plate).

## Material estimates

| Reference | Crown | Integrated base | Total |
| --- | ---: | ---: | ---: |
| v1.3 / fixed PETG benchmark | 187.02 g | 153.00 g | 340.02 g |
| v1.5 / same PETG benchmark | 25.77 g | 40.84 g | 66.61 g |
| v1.6 / same PETG benchmark | 33.48 g | 91.27 g | 124.75 g |
| v1.7 / same PETG benchmark | 33.48 g | 81.96 g | 115.44 g |
| **v1.8 / same PETG benchmark** | **33.48 g** | **76.43 g** | **109.91 g** |
| v1.6 / PLA standard | 29.65 g | 83.45 g | 113.10 g |
| v1.7 / PLA standard | 29.65 g | 77.71 g | 107.36 g |
| **v1.8 / PLA standard** | **29.65 g** | **72.44 g** | **102.09 g** |

The PLA standard estimate is 5.27 g below v1.7. The fixed PETG comparison saves **67.68%** against v1.3; the earlier 80% target remains unmet. Common PETG benchmark settings are five walls, six top/bottom layers, 35% gyroid and no brim. Supports: both ON in v1.3, crown only ON in v1.5, both OFF in v1.6/v1.7/v1.8. PLA standard uses another process; do not mix it with the PETG rows to calculate a reduction.

All weights are slicer estimates, not measured prints. Purge, calibration, failures, extra brim, sealant and the optional sample are excluded. `review/material_comparison.json` records settings, hashes and source revisions; current evidence is in `review/revision-v1.8-slicing/`. No sliced G-code is shared.

## Assembly and physical checks

An intact old crown can be trial-fitted with the new base. A tight fit does not prove an ant seal. Fully seat the crown with a thin continuous bonded seal around its bottom ring, radius **79.2–80 mm**. Keep sealant inside the locating rim, preserve the liquid trough and cure as directed for the actual material and conditions. Test the trough with plain water before adding liquid; leave spill margin and follow the product label. Tape may line the continuous upper inverted ledge or sloped wall.

Inspect and smooth burrs or rough layer lines on exposed leg and channel surfaces without damaging the seating ring or intact panel. Check all six feet on a flat table, root integrity, complete panel and channel surfaces, and the mating seam. Center the original kettle power base and place its contact feet on deep beams or beam/ring junctions. The kettle is 1.7 L, but base diameter, full mass, center of mass and contact temperature are unmeasured. **3.5 kg is a validation target, not a rated capacity.** New stability, stiffness, heat tolerance, leakage and ant performance have not been physically tested. PLA printing does not establish suitability for the operating environment.

Cords, walls and nearby objects can bypass the barrier. Isolate those routes and retain ventilation and cable clearance. Smooth and inverted surfaces alone do not guarantee ant exclusion.

## Source and review

`parameters.json` drives the Python builder; `model.scad` is matching editable OpenSCAD geometry. Rebuild models and the offline viewer:

```sh
python3 -m venv /tmp/ant-kettle-cad-env
/tmp/ant-kettle-cad-env/bin/pip install -r tools/requirements.txt
/tmp/ant-kettle-cad-env/bin/python tools/generate.py
/tmp/ant-kettle-cad-env/bin/python tools/build_preview.py
```

Changed geometry requires new slicing records. `tools/compare_material.py` resolves installed Bambu Studio profiles and slices locally without contacting a printer. `--filament 'Generic PLA @BBL A1' --standard --support off` selects the recorded PLA check. Unchanged objects may reuse records only after exact STL hash matching, preserving their source revision.

`review/physical_feedback_revision_validation.json` records six contact rings and a clear 10 mm underside band, zero geometry outside the round tray, zero exposed outer rib ends, retained mating surfaces, complete panel and channel clearance. `review/support_free_parts_validation.json` distinguishes new base slicing from reused upper results. Meshes are closed, consistently oriented and one connected body per print file. HTML data, scripts and links are checked; face normals avoid misleading smoothing across sharp joins. Browser interaction has not been automatically retested.

Local `review/previous-v1.5/`, `review/previous-v1.6/` and `review/previous-v1.7/` files support historical comparisons and are excluded from the community ZIP. Historical comparison scripts require those files; normal generation and preview rebuilding do not. Three.js v0.160.1 is bundled under MIT in `tools/THREE-LICENSE.txt`.

Date: 2026-10-09. Units: mm.

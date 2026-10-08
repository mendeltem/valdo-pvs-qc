# valdo-pvs-qc

Quality-control pages for enlarged perivascular space (PVS) detection on the public VALDO 2021 Task 1 data (12 cases, rater-1 reference):

**https://mendeltem.github.io/valdo-pvs-qc/**

- `slices/` our chain by verdict (green detected, yellow false alarm, red missed), leave-one-case-out
- `compare/` the chain versus its parts: classifier-kept, DRIPS-T2, MedNet-T1, candidate pool

Built with the shared QC generator (`qc_slice_viewer`, manifest-driven; same page as the microbleed project
[valdo-cmb-qc](https://github.com/mendeltem/valdo-cmb-qc)). Pooled counts on the pages equal the metric script's
counts (903 / 335 / 878). Research and teaching use only.

Data: VALDO 2021 Task 1, Zenodo 10.5281/zenodo.4687995, CC BY-NC 4.0; attribution and funding lines on the landing page.

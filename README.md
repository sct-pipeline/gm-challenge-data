![](https://github.com/neuropoly/gm_challenge/blob/master/doc/logo_challenge.png)

# Spinal Cord Gray Matter Imaging Challenge - Data

Dataset for the gray matter acquisition challenge. The main repository of the challenge is at: https://github.com/sct-pipeline/gm-challenge. 


Data are organized according to BIDS:

~~~
├── derivatives
│   └── labels
│       └── sub-10062
│           └── anat
│               ├── sub-10062_run-1_T2starw_gmseg-manual.json
│               ├── sub-10062_run-1_T2starw_gmseg-manual.json
│               ├── sub-10062_run-1_T2starw_seg-manual.json
│               └── sub-10062_run-1_T2starw_seg-manual.json
│
└── sub-10062
    └── anat
        ├── sub-10062_run-1_T2starw.json
        ├── sub-10062_run-1_T2starw.nii.gz
        ├── sub-10062_run-2_T2starw.json
        └── sub-10062_run-2_T2starw.nii.gz
~~~

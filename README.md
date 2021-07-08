# study-template

File structure for creating a new neuroimaging study.

Start by cloning this repo to the server in the projects directory

```
cd /data00/projects
git clone https://github.com/cnlab/study-template.git
```

Once cloned, rename the `study_template` folder for your project and remove git tracking.

```
cd /data00/projects/[project name]
rm -rf .git
```

Core scripts in the CN lab pipeline are in `/data00/tools/cnlab_pipeline`. 

## Repo file structure

```
├── data
│	├── behavioral
│	├── bids_data
│	│	└── derivatives
│	│		├── DWI
│	│		├── FC
│	│		├── MVPA
│	│		├── PE
│	│		├── PPI
│	│		├── ROI
│	│		├── fmriprep
│	│		├── freesurfer
│	│		├── nipype
│	│		├── rsfMRI
│	│		└── sMRI
│	└── task_logs
└── scripts
    ├── BIDS
    ├── DWI
    ├── FC
    ├── FMRIPREP
    ├── L1
    	└── motion
    ├── L2
    	└── thresholding
    ├── MVPA
    ├── PE
    ├── PPI
    ├── ROI
    ├── behavioral
    ├── rsfMRI
    └── sMRI
```

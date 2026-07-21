# Data-for-dual-timescale-optical-tracking

This repository contains the experimental data associated with our manuscript on dual-timescale optical tracking.

## Data Description

The uploaded files include the experimental data used to generate the results presented in the main text and Supplementary Information. The data are organized according to the corresponding figure numbers and panel labels in the manuscript.

- `.mat` files contain the experimental measurements or processed numerical results used for analysis and figure generation.
- `.png` files provide corresponding image results or visual previews where available.
- Folders labeled `Proposed` and `RLS` contain results obtained using the respective methods described in the manuscript.
- Files named `step_XXXX` correspond to different sequential steps or measurement states in the associated experiment.
- Files named `*scanning result.mat` (for example, `Fig.2-g-'+'scanning result.mat`, `Fig.2-g-'POLY'scanning result.mat`, and `Fig.2-g-'XJTU'scanning result.mat`) contain the original focusing result of each acquired frame as well as the accumulated result obtained by superimposing the focal points from all frames. The accumulated result corresponds to the final scanning image presented in the manuscript, allowing it to be traced back to and verified against the frame-by-frame focusing data.

## File Organization

```text
dataset/
|-- Figure1/                 # Data for Figure 1
|-- Figure2/                 # Data for Figure 2
|   `-- Fig.2-d/
|-- Figure3/                 # Data for Figure 3
|   |-- Fig.3-c-Proposed/
|   |-- Fig.3-c-RLS/
|   |-- Fig.3-g-Proposed/
|   `-- Fig.3-g-RLS/
|-- Figure4/                 # Data for Figure 4
|   `-- Fig.4-b/
|-- Figure S2/               # Data for Supplementary Figure S2
|   |-- Fig.S2-a-Proposed/
|   |-- Fig.S2-a-RLS/
|   `-- ...
|-- Figure S3/               # Data for Supplementary Figure S3
|   |-- Fig.S3-a-Proposed/
|   |-- Fig.S3-a-RLS/
|   `-- ...
|-- Figure S4/               # Data for Supplementary Figure S4
|   `-- ...
`-- Figure S6/               # Data for Supplementary Figure S6
    `-- ...
```

## Software

MATLAB is recommended for loading and analyzing the `.mat` files. 

## Citation

If you use these data in your research, please cite the associated manuscript:

```text
[Citation information will be added after publication.]
```

## Contact

For questions regarding the dataset, please contact:

Zian Wang  
Email: [ziaan.wang@connect.polyu.hk]

# Surrogate Models for Additive Manufacturing
[Data Download](https://drive.google.com/drive/u/0/folders/1jCzhg4bwJk7lqaEBTcfoWZch0BIdxavM)


#### File Structure
```plaintext
additivemodels/
├── data/
│   ├── processed/
│   │   ├── repaired_graph_dataset1.json
│   │   └── repaired_graph_dataset2.json
│   ├── raw/
│   │   ├── rawcloud/
│   │   ├── rawnorm/
│   │   ├── repaired_files/
│   │   ├── raw_cloud.json
│   │   ├── raw_norm.json
│   │   └── sanitized_dict.json
├── models/
├── notebooks/
│   └── preprocessing/
│       ├── mesh_graph_nets.ipynb
│       ├── stl_converter.ipynb
│       └── gnn.ipynb
├── .gitignore
└── README.md
```

All data and labels pulled from: https://github.com/TianshuangQiu/AdditiveParts

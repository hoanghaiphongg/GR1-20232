
### Dataset structure for PraNet Implement
Tensorflow [tf.data](https://www.tensorflow.org/guide/data) API is used to create Input Data pipeline.   
<b>In order to create a data pipeline for Image and Mask, the folder should be structured likewise:</b>
```
polyps_dataset
├── images [1000 files]
│   ├── 1.jpg
│   ├── 2.jpg
│   └── 3.jpg
└── masks [1000 files]
    ├── 1.jpg
    ├── 2.jpj
    └── 3.jpj



## Dataset source for PraNet Implement
* [Kvasir SEG dataset](https://datasets.simula.no/kvasir-seg/)




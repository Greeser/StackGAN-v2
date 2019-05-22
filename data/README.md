### Zappos dataset

Zappos dir

```bash
zappos
├── images
│   ├── Boots
│   ├── Sandals
│   ├── Shoes
│   └── Slippers
├── test
│   ├── class_info.pickle
│   ├── filenames.pickle
│   └── simple-embeddings.pickle
└── train
    ├── class_info.pickle
    ├── filenames.pickle
    └── simple-embeddings.pickle
```

### Glove dir
```
glove_6B/
├── glove.6B.100d.txt
├── glove.6B.200d.txt
├── glove.6B.300d.txt
├── glove.6B.50d.dat
│   ├── __attrs__
│   ├── data
│   └── meta
├── glove.6B.50d_idx.pkl
├── glove.6B.50d.txt
└── glove.6B.50d_words.pkl
```
# StackGAN-v2

**Data**

1. Download our preprocessed char-CNN-RNN text embeddings for [birds](https://drive.google.com/open?id=0B3y_msrWZaXLT1BZdVdycDY5TEE) and save them to `data/`
  - [Optional] Follow the instructions [reedscot/icml2016](https://github.com/reedscot/icml2016) to download the pretrained char-CNN-RNN text encoders and extract text embeddings.
2. Download the [birds](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html) image data. Extract them to `data/birds/`
3. Download [ImageNet](http://image-net.org/download) dataset and extract the images to `data/imagenet/`
4. Download [LSUN](https://github.com/fyu/lsun) dataset and save the images to `data/lsun`

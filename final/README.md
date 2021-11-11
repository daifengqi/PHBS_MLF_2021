# Text-Based Firm Similarity

## reference

- **Paper**

https://doi.org/10.1086/688176

- **Doc2vec**

https://radimrehurek.com/gensim/index.html

## structure

- **Read**

![read.png](https://i.loli.net/2021/11/10/MiUpwOt6clav2Pn.png)

we can define what type of report ( *FILING_10K* ) we want to request

![save.png](https://i.loli.net/2021/11/10/xQsyjZzd7BH2T4l.png)

- **Parse ** (34GB -> 140MB)

with the help of `re` and `bs4` packages.

![image.png](https://i.loli.net/2021/11/10/CutjHvmJXBw2kUy.png)

- **Tokenize** (46MB, one file)

many steps... ( see in *comment* )

![image.png](https://i.loli.net/2021/11/10/esA8cTKNwuObQk1.png)

We will use `doc.feather` in `.ipynb` file.

## word2vec, doc2vec

![Vectors](https://multithreaded.stitchfix.com/assets/images/blog/vectors.gif)

[A Word is Worth a Thousand Vectors](https://multithreaded.stitchfix.com/blog/2015/03/11/word-is-worth-a-thousand-vectors/)

- pick words (what the original paper does)
- word2vevc
- doc2vec



### jupyter config

```
jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10
```


# CIC
An **C**ustermers **I**nteraction Dataset of **C**lothing of Alibaba (CIC)


## Overview
This customer interaction dataset is collected from the TaoBao.com of Alibaba. It is one of the most popular e-commerce websites in China.
The data format is Simplified Chinese(简体中文).
Specifically, this dataset mainly focuses on the product category -- ``clothing''.
This dataset records the interaction of the customers and the products.
The statistics information of the dataset is shown in following table.
<div align="center">
  <img src="https://github.com/zxjwudi/materials/blob/main/datasetStatistic.png" width="600px" />
</div>

In this dataset, there are 1,897,339 records of customers' interactions.
Every interaction record contains a query, a customer ID, a product ID, a product title and the corresponding attribute set of this product.
The attribute sets of this dataset contain both concrete product attributes and abstract product attributes.
The product attributes of existing tend to be noisy, because most of the annotations are collected by crawling fashion product attribute-level descriptions or extracted from the title directly from large online shopping websites.
Unlike these datasets, the attributes in our dataset are annotated manually by fashion and clothing experts.
So the accuracy and quality of this dataset is very high.


## Usage Notes
Researchers who are interested in CIC dataset can access this dataset from the [**GoogleDrive**](https://drive.google.com/file/d/1IMf7JtDHmCrLkuUTiY79deiWzTZ62BzA/view?usp=sharing) and [**BaiDuYun**](https://pan.baidu.com/s/1HMM6t2RWuvPbvGwYP-TTNg) with code (9jqb). 


## Citation

If you find this dataset is helpful, please kindly consider citing the following papers:

Zhao, Xuejiao, et al. "Heterogeneous star graph attention network for product attributes prediction." Advanced Engineering Informatics. 51, 101447. 2022. 

```
@article{ZHAO2022101447,
title = {Heterogeneous star graph attention network for product attributes prediction},
author = {Xuejiao Zhao and Yong Liu and Yonghui Xu and Yonghua Yang and Xusheng Luo and Chunyan Miao},
journal = {Advanced Engineering Informatics},
volume = {51},
pages = {101447},
year = {2022},
publisher={Elsevier}
}
```

If you have any questions or concerns, please kindly email to [**Xuejiao Zhao**](xjzhao@ntu.edu.sg).

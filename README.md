# Alibaba-Custermers-Interaction-Dataset


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

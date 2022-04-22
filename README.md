# Product Packaging
Project Product Packaging

- Topic : Machine Learning
- Programming languages : R
- Packages : -
- Algorithms used : -


## Introduction  : 
DQLab.id Fashion is a fashion shop that sells various products such as jeans, shirts, cosmetics, and others. Although it is quite developed, but the increasing number of competitors and many products whose stocks are still large, it certainly worries DQLab.id Fashion managers. One solution is to create innovative packages. Where products that were previously unsold but have market share can even be packaged and sold.

## Data :
Dataset in TSV format (Tab Separated Value)with 33,669 rows (3,450 transaction codes).
The data tidied up by containing only two variables :

- Kode Transaksi
- Nama Barang
Other variables such as price, date, number of purchases, etc not included because these two variables sufficient.

## Task :
Several steps were taken to complete this project. First is prepare library and dataset. Then the raw data is cleaned up and scaled using standardization and normalization prior to modeling. And to realize this, using the A priori algorithm of the Arules package throughout this project.

- Get insight into the top 10 and bottom 10 of the products sold.
- Get a list of all product package combinations with strong correlations.
- Get a list of all product package combinations with specific items.

## Summary :
From the results, we get the results of 3 combinations each for the 2 slow-moving items that have the strongest association,

Tas Makeup:
- {Baju Renang Anak Perempuan, Tas Pinggang Wanita} => {Tas Makeup}
- {Baju Renang Anak Perempuan, Tas Ransel Mini} => {Tas Makeup}
- {Baju Renang Anak Perempuan, Celana Pendek Green/Hijau} => {Tas Makeup}

Baju Renang Pria Anak-anak:
- {Gembok Koper, Tas Waist Bag} => {Baju Renang Pria Anak-anak}
- {Flat Shoes Ballerina, Gembok Koper} => {Baju Renang Pria Anak-anak}
- {Celana Jeans Sobek Wanita, Jeans Jumbo} => {Baju Renang Pria Anak-anak}

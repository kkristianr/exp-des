## Table 2 (with Joan's CPU)
| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |
| FM-woUF      |             |             |             |            |
| FM-maskUF      |  0.0756   |     0.0577        |  0.1048           |   9.6185         |
| FM-Fairco      |             |             |             |            |
| FM-Diversity      |             |             |             |            |
| FM-UCI      |   0.0767          |     0.0592        |     0.0777        |     9.8802     |
| NFM-woUF      |             |             |             |            |
| NFM-maskUF      |   0.0759          |      0.0575       |  0.1378            |  9.9740        |
| NFM-Fairco      |             |             |             |            |
| NFM-Diversity      |             |             |             |            |
| NFM-UCI      |      0.0767    |      0.0596       |   0.0760          |     9.9000       |

## Table 3
Performance comparison between UCI and the baseline under the fine-grained user-feature controls. The best results are highlighted in bold and the second best ones are underlined. 

### Table 3.1 FM (with IVA's cpu)


| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | DIS-EUC(down) |Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |    |
| FM-woUF      |             |             |             |            |   |
| FM-changeUF      |   0.0858          |       0.0649      |      missing       |     0.0548       |  8.6859 |
| FM-Fairco      |             |             |             |            |   |
| FM-Diversity      |             |             |             |            |    |
| FM-UCI      | 0.087    |   0.0661     |  0.0979       |    0.0500      |  9.0304 |



### Table 3.1 FM (with GPU cuda)

| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | DIS-EUC(down) |Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |    |
| FM-woUF      |             |             |             |            |   |
| FM-changeUF      | 0.0858   |   0.0649     |   0.1152       |    0.0548       |  8.6859 |
| FM-Fairco      |             |             |             |            |   |
| FM-Diversity      |             |             |             |            |    |
| FM-UCI      |   0.087        |   0.0661       | 0.0979         |   0.0500        |  9.0304  |

### Table 3.2 NFM (run on GPU with Cuda driver)

| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | DIS-EUC(down) |Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |    |
| NFM-woUF      |             |             |             |            |   |
| NFM-changeUF      | 0.0847    |  0.063  |   0.1048      |    0.0417    | 9.5193 |
| NFM-Fairco      |             |             |             |            |   |
| NFM-Diversity      |             |             |             |            |    |
| NFM-UCI      |    0.0844        |  0.0635        |    0.0844     |   0.0343        |  9.6439  |


### Table 4 ML-1M (run on CPU)

| Method         | Recall | NDCG   | W-NDCG | MCD    | TCD    | Coverage |
| -------------- | ------ | ------ | ------ | ------ | ------ | -------- |
| Random         |        |        |        |        |        |          |
| FM             | 0,0659 | 0,0536 | 0,0485 | 0,5994 | 0,2222 | 8,66     |
| FM-woIF        |        |        |        |        |        |          |
| FM-Fairco      |        |        |        |        |        |          |
| FM-Diversity   |        |        |        |        |        |          |
| FM-Reranking   | 0,0761 | 0,0637 | 0,0603 | 0,1    | 0,3099 | 8,9409   |
| FM-C-UCI       | 0,077  | 0,0665 | 0,063  | 0,2466 | 0,3334 | 9,1206   |
| FM-F-UCI (UB)  | 0,2095 | 0,1704 | 0,1792 | 0,3544 | 1      | 8,0712   |
| NFM            | 0,0651 | 0,056  | 0,0501 | 0,5748 | 0,2321 | 8,8854   |
| NFM-woIF       |        |        |        |        |        |          |
| NFM-Fairco     |        |        |        |        |        |          |
| NFM-Diversity  |        |        |        |        |        |          |
| NFM-Reranking  | 0,0555 | 0,0484 | 0,0453 | 0,0252 | 0,31   | 8,2002   |
| NFM-C-UCI      | 0,0778 | 0,0687 | 0,0647 | 0,2753 | 0,3119 | 9,0744   |
| NFM-F-UCI (UB) | 0,2125 | 0,1729 | 0,182  | 0,3319 | 1      | 8,2299   |

### Table 4 Amazon Book
| Method         | Recall | NDCG   | W-NDCG | MCD    | TCD    | Coverage |
| -------------- | ------ | ------ | ------ | ------ | ------ | -------- |
| Random         |        |        |        |        |        |          |
| FM             | 0,0178 | 0,0095 | 0,0085 | 0,5353 | 0,2306 | 3,0175   |
| FM-woIF        |        |        |        |        |        |          |
| FM-Fairco      |        |        |        |        |        |          |
| FM-Diversity   |        |        |        |        |        |          |
| FM-Reranking   | 0,0178 | 0,0142 | 0,0142 | 0,0026 | 0,2845 | 3,0196   |
| FM-C-UCI       | 0,0173 | 0,0141 | 0,0146 | 0,0213 | 0,631  | 2,0768   |
| FM-F-UCI (UB)  | 0,0338 | 0,027  | 0,0327 | 0,0023 | 1      | 1,0002   |
| NFM            | 0,0121 | 0,0102 | 0,0088 | 0,5488 | 0,2293 | 2,9818   |
| NFM-woIF       |        |        |        |        |        |          |
| NFM-Fairco     |        |        |        |        |        |          |
| NFM-Diversity  |        |        |        |        |        |          |
| NFM-Reranking  | 0,018  | 0,0144 | 0,0144 | 0,0025 | 0,5421 | 3,0184   |
| NFM-C-UCI      | 0,0181 | 0,0148 | 0,0154 | 0,0049 | 0,6779 | 1,419    |
| NFM-F-UCI (UB) | 0,0338 | 0,0276 | 0,0327 | 0,0023 | 1      | 1,0002   |

## Table 5 
| Method    | Variants | Recall | NDCG   | W-NDCG | MCD    | TCD | Coverage |
| --------- | -------- | ------ | ------ | ------ | ------ | --- | -------- |
| FM-F-UCI  | w/o CI   | 0,2094 | 0,1689 | 0,1777 | 0,3587 | 1   | 7,9519   |
| FM-F-UCI  | w/ CI    | 0,2095 | 0,1704 | 0,1792 | 0,3544 | 1   | 8,0712   |
| NFM-F-UCI | w/o CI   | 0,2094 | 0,1687 | 0,1775 | 0,3525 | 1   | 8,016    |
| NFM-F-UCI | w/ CI    | 0,2125 | 0,1729 | 0,182  | 0,3319 | 1   | 8,2299   |

## Figure 6 
![Figures 6 from paper](https://github.com/kkristianr/exp-des/blob/main/figures/Figure%206.png?raw=true)

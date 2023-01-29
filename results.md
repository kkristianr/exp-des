## Table 2 (with EMIL's gpu)
Performance comparison between UCI and the baselines under the coarse-grained user-feature controls. 

| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |
| FM-woUF      |             |             |             |            |
| FM-maskUF      |  0.0671   |     0.0399        |  0.1307           |   6.0562         |
| FM-Fairco      |             |             |             |            |
| FM-Diversity      |             |             |             |            |
| FM-UCI      |        0.0314     |      0.0209       |   0.0006          |     6.3257       |
| NFM-woUF      |             |             |             |            |
| NFM-maskUF      |   0.0652          |      0.0386       | 0.1662            |   6.4943         |
| NFM-Fairco      |             |             |             |            |
| NFM-Diversity      |             |             |             |            |
| NFM-UCI      |   0.0394          |     0.0239        |     0.0011        |     6.7156       |

## Table 3 (with IVA's cpu)


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





### Table 3.1 FM (with Emil's gpu with .long() )

| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | DIS-EUC(down) |Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |    |
| FM-woUF      |             |             |             |            |   |
| FM-changeUF      | 0.0716    |   0.0431     |   0.1412       |    0.1314       |  6.0806 |
| FM-Fairco      |             |             |             |            |   |
| FM-Diversity      |             |             |             |            |    |
| FM-UCI      |   0.0252         |   0.0182       | 0.0011         |   0.0009        |  6.7505  |

### Table 3.2 NFM

| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | DIS-EUC(down) |Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |    |
| NFM-woUF      |             |             |             |            |   |
| NFM-changeUF      | 0.073    |  0.0436  |   0.1321      |    0.1228    | 6.0377 |
| NFM-Fairco      |             |             |             |            |   |
| NFM-Diversity      |             |             |             |            |    |
| NFM-UCI      |    0.0366        |  0.0228        |     0.0007     |   0.0009        |  6.4502  |

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

### Table 3.2 NFM (with GPU cuda)

| -      | Recall (up) | NDCG (up)   | Iso-Index (down) | DIS-EUC(down) |Coverage(up) |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Random      |             |             |             |            |    |
| NFM-woUF      |             |             |             |            |   |
| NFM-changeUF      | 0.0847    |  0.063  |   0.1048      |    0.0417    | 9.5193 |
| NFM-Fairco      |             |             |             |            |   |
| NFM-Diversity      |             |             |             |            |    |
| NFM-UCI      |    0.0844        |  0.0635        |    0.0844     |   0.0343        |  9.6439  |

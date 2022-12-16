# PoQuAD
**PoQuAD** is the Polish Question Answering Dataset. It is modeled on the SQuAD 2.0, including the impossible questions. Additionally it includes a generative answer layer, which allows to train models to return the most natural sounding responses to the queries. The textual data are original Polish texts from Wikipedia, and they were selected to reflect the topics most relevant to Polish speakers.

### The dataset consists of

| Split | Size  |             |
|-------|-------|-------------|
| Train | 37414 |             |
| Dev   | 4667  |             |
| Test  | 4680  | (nonpublic) |
| **Total** | **46761** |     |


### Baseline Evaluation results

#### Extractive QA

**HERBERT-Large**
| Metric      | Value  |
|-------------|---------|
| HasAns Exact Match | 64.27 |
| HasAns F1          | 80.55 |
| NoAns Exact Match  | 65.77 |
| Total Exact Match  | 64.53 |
| Total F1           | 77.96 |

#### Generative QA

**PLT5-Large**
| Metric      | Value  |
|-------------|---------|
| HasAns Exact Match | 66.73 |
| HasAns F1          | 80.84 |
| NoAns Exact Match  | 52.13 |
| Total Exact Match  | 64.17 |
| Total F1           | 75.81 |

### Citing

```
@misc{PoQuAD,
  author = {{Ryszard Tuora, Natalia Zawadzka-Paluektau, Cezary Klamra, Aleksandra Zwierzchowska and Łukasz Kobyliński}},
  title = {PoQuAD: Polish Question Answering Dataset},
  year = {2022},
  note = {Repository: https://github.com/ipipan/poquad},
}
```

### Acknowledgments
This work was supported by the European Regional Development Fund as a part of the 2014-2020 Smart Growth Operational Programme: (1) Intelligent travel search system based on natural language understanding algorithms, project no. POIR.01.01.01-00-0798/19; (2) CLARIN - Common Language Resources and Technology Infrastructure, project no. POIR.04.02.00-00C002/19. The owner of the dataset is the Wrocław University of Science and Technology.

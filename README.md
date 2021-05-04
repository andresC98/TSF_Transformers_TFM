# Time Series Forecasting using Transformers - Thesis Repository

***(Work in Progress)*** Repository containing my Master Thesis for the M.Sc. Big Data Analytics, titled *"Time Series Forecasting using Transformers"*.

- **Abstract:** *TODO*
- **Author:** *Andrés Carrillo López*
- **Supervisor:** *Pablo Martínez Olmos*

---

### Repository Folder Structure:

- `img` folder: contains images used in this README document and other relevant images.
- `code_notebooks` folder: contains *Python* code and notebooks (*.ipynb*) used for the experiments.
- `data` folder: contains the benchmark (public) datasets used in the experiments. The complete processed ones are compressed in [bzip2](https://www.geeksforgeeks.org/bzip2-command-in-linux-with-examples/).
- `.pdf` file: thesis/summary document.

#### Trained models: 
For those models that training took considerable time, their trained checkpoint-model (heavy) files can be found [here available for download](https://drive.google.com/drive/folders/18SMaGidTDNXnJOI8_b7KUbnwvdns1AIu?usp=sharing).

---

### Test Notebooks:

**Important note**: to view notebooks from these links, you must access them through a **UC3M mail** account. If you do not have a UC3M account, download the notebooks from the `code_notebooks` folder and open them in a [Google Colaboratory](https://colab.research.google.com/) environment.


- Benchmark datasets (*Traffic* and *Electricity*) Retrieval and Aggregation: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tJsg_BSrCwPbeVFDrl-fKZnzds2HnA5L#offline=true&sandboxMode=true)
- *Classical forecast methods* Tests: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11TkLkG_5l2bml42tw7OqZVnNHROCX-lA#offline=true&sandboxMode=true)
- *Temporal Fusion Transformer* (TFT) Tests:: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz#offline=true&sandboxMode=true)
- *Informer* Tests: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10oPFrjSF3MwNTYsYafRGC6zJzUTsuv6m#offline=true&sandboxMode=true)
- *DeepAR* Tests: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1e-BVkAoYoKnNn_6xI-XWUNbVf110-QxX#offline=true&sandboxMode=true)


---
### Current progress and milestones (WIP):

- [x] Benchmark Datasets (*[Traffic](https://archive.ics.uci.edu/ml/datasets/PEMS-SF), [Electricity](https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014)*) Datasets retrieval and preprocessing.
- [x] Tests Forecasting using [Temporal Fusion Transformer (TFT)](https://arxiv.org/abs/1912.09363) architecture.
- [x] Tests Forecasting using [DeepAR](https://arxiv.org/abs/1704.04110) architecture.
- [x] Tests Forecasting using [Informer](https://arxiv.org/pdf/2012.07436.pdf) Transformer architecture.
- [x] Tests Forecasting using classical methods ((S)ARIMA, SES and Holt-Winters).
- [x] Ensure proper comparability between final error metrics in models/datasets.
- [x] Provide links for experiment notebooks in *GoogleColab* playground notebooks.
- [ ] Final review / decoration of Test notebooks.
- [ ] Write Master Thesis (Current progress: 10%).

---
### Some extracted results:

- Benchmark results (Traffic and Electricity datasets, 1-day and 1-week forecast scenarios) Mean Absolute Errors:

|                          |   ARIMA  |    SES   | Holt-Winters | DeepAR  | Informer | TFT     |
|--------------------------|:--------:|:--------:|--------------|---------|----------|---------|
|    **Traffic (1-day)**   |  0.0188  |  0.0640  | 0.0236       | 0.0161  | 0.01050  | 0.0099  |
|   **Traffic (1-week)**   |  0.0198  |  0.0757  | 0.0336       | 0.0147  | 0.01251  | 0.0105  |
|  **Electricity (1-day)** | 84.2201  | 307.4311 | 75.6006      | 88.3992 | 69.8323  | 37.0946 |
| **Electricity (1-week)** | 165.0958 | 308.4780 | 98.3879      | 64.1848 | 102.0774 | 50.8038 |

- Some images from notebook tests so far: sample plots extracted from the *TFT* model forecasts, with attention and feature relevances plots:

![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electr_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electrimp_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_traffic_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_trafficimp_sample.png?raw=true)

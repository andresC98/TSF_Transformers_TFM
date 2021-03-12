# Time Series Forecasting using Transformers - Thesis Repository

***(Work in Progress)*** Repository containing my Master Thesis for the M.Sc. Big Data Analytics, titled *"Time Series Forecasting using Transformers"*.

- **Abstract:** *TODO*
- **Author:** *Andrés Carrillo López*
- **Supervisor:** *Pablo Martínez Olmos*

---

### Repository Folder Structure:

- `ref/img` folders: contains references and images folder for the thesis (*LaTeX*) project.
- `code_notebooks` folder: contains *Python* code and notebooks (*.ipynb*) used for the experiments. 
- `.tex` file: contains thesis *LaTeX* document.

---
### Current progress and milestones (WIP):

- [x] Benchmark Datasets (*[Traffic](https://archive.ics.uci.edu/ml/datasets/PEMS-SF), [Electricity](https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014)*) Datasets retrieval and preprocessing.
- [x] Tests Forecasting using [Temporal Fusion Transformer (TFT)](https://arxiv.org/abs/1912.09363) architecture.
- [ ] Forecasting using [DeepAR](https://arxiv.org/abs/1704.04110) (baseline)
- [ ] Forecasting using classical methods (ETS, ARIMA,...)
- [ ] Tests implementing other transformer models (e.g. [Enhancing the Locality...](https://www.semanticscholar.org/paper/Enhancing-the-Locality-and-Breaking-the-Memory-of-SHIYANG-Jin/36e30516683032634975c53e60f3737b6e35ff80) paper)
- [ ] Provide links for experiment notebooks in *GoogleColab* playground notebooks.

---
### Relevant Results (WIP):

Some images from relevant tests so far (Electr and Traffic datasets):

![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electr_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electrimp_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_traffic_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_trafficimp_sample.png?raw=true)

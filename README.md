# Time Series Forecasting using Transformers - Thesis Repository

***(Work in Progress)*** Repository containing my Master Thesis for the M.Sc. Big Data Analytics, titled *"Time Series Forecasting using Transformers"*.

- **Abstract:** *TODO*
- **Author:** *Andrés Carrillo López*
- **Supervisor:** *Pablo Martínez Olmos*

---

### Repository Folder Structure:

- `ref/img` folders: contains references and images folder for the thesis (*LaTeX*) project.
- `code_notebooks` folder: contains *Python* code and notebooks (*.ipynb*) used for the experiments.
- `code_models` folder: contains *Python* code of the model(s) implemented outside libraries. 
- `.tex` file: contains thesis *LaTeX* document.

---

### Test Notebooks (Colab links, TODO):

TODO, placeholder links.

- *Temporal Fusion Transformer* (TFT) test: *Traffic* benchmark - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing) - *Electricity* benchmark - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *Informer* test: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *DeepAR* test: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *Classical forecast methods* test: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)

---
### Current progress and milestones (WIP):

- [x] Benchmark Datasets (*[Traffic](https://archive.ics.uci.edu/ml/datasets/PEMS-SF), [Electricity](https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014)*) Datasets retrieval and preprocessing.
- [x] Tests Forecasting using [Temporal Fusion Transformer (TFT)](https://arxiv.org/abs/1912.09363) architecture.
- [x] Tests Forecasting using [DeepAR](https://arxiv.org/abs/1704.04110) architecture.
- [ ] Tests Forecasting using [Informer](https://arxiv.org/pdf/2012.07436.pdf) Transformer architecture.
- [ ] Forecasting using classical methods (ETS, ARIMA,...) (classical time series forecasting baselines)
- [ ] Annotate / Decorate (last finishing touch) Test notebooks.
- [ ] Provide links for experiment notebooks in *GoogleColab* playground notebooks.
- [ ] Write Master Thesis (Current progress: 1%).

---
### Relevant Results (WIP):

Some images from relevant tests so far (*Electricity* and *Traffic* datasets):

![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electr_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electrimp_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_traffic_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_trafficimp_sample.png?raw=true)

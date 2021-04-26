# Time Series Forecasting using Transformers - Thesis Repository

***(Work in Progress)*** Repository containing my Master Thesis for the M.Sc. Big Data Analytics, titled *"Time Series Forecasting using Transformers"*.

- **Abstract:** *TODO*
- **Author:** *Andrés Carrillo López*
- **Supervisor:** *Pablo Martínez Olmos*

---

### Repository Folder Structure:

- `ref/img` folders: contains references and images folder for the thesis (*LaTeX*) project.
- `code_notebooks` folder: contains *Python* code and notebooks (*.ipynb*) used for the experiments.
- `data` folder: contains the benchmark (public) datasets used in the experiments. The complete processed ones are compressed in [bzip2](https://www.geeksforgeeks.org/bzip2-command-in-linux-with-examples/).
- `utils` folder: contains *Python* code of some helper and plotting functions developed for the thesis. 
- `.tex` file: contains thesis *LaTeX* document.

#### Trained models: 
For those models that training took considerable time, their trained checkpoint-model (heavy) files can be found [here available for download](https://drive.google.com/drive/folders/18SMaGidTDNXnJOI8_b7KUbnwvdns1AIu?usp=sharing).

---

### Test Notebooks (Colab links, TODO):

TODO, placeholder links. While thesis not published: open in Colab the notebooks in the `code_notebooks` folder, not from these link.

- Benchmark datasets (*Traffic* and *Electricity*) Retrieval and Aggregation: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *Temporal Fusion Transformer* (TFT) Tests:: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *Informer* Tests: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *DeepAR* Tests: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)
- *Classical forecast methods* Tests: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PhP8KzPXd0NlTXEx3s2PG0HgPWtvZyyz?usp=sharing)

---
### Current progress and milestones (WIP):

- [x] Benchmark Datasets (*[Traffic](https://archive.ics.uci.edu/ml/datasets/PEMS-SF), [Electricity](https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014)*) Datasets retrieval and preprocessing.
- [x] Tests Forecasting using [Temporal Fusion Transformer (TFT)](https://arxiv.org/abs/1912.09363) architecture.
- [x] Tests Forecasting using [DeepAR](https://arxiv.org/abs/1704.04110) architecture.
- [x] Tests Forecasting using [Informer](https://arxiv.org/pdf/2012.07436.pdf) Transformer architecture.
- [x] Tests Forecasting using classical methods ((S)ARIMA, SES and Holt-Winters).
- [x] Hyperparameter Tuning and final forecasts/interpretation (generate plots) for TFT, DeepAR and Informer models.
- [ ] Annotate / Decorate (last finishing touch) Test notebooks.
- [ ] Provide links for experiment notebooks in *GoogleColab* playground notebooks.
- [ ] Write Master Thesis (Current progress: 5%).

---
### Relevant Results (WIP):

Some images from relevant tests so far (*Electricity* and *Traffic* datasets):

![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electr_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_electrimp_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_traffic_sample.png?raw=true)
![alt text](https://github.com/andresC98/TSF_Transformers_TFM//blob/main/img/repo_tft_trafficimp_sample.png?raw=true)

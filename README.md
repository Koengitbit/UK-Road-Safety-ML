# Traffic Accident Severity Prediction

**Auteurs:** Koen van der Hoeven & Lars Tovar
**Opleiding:** HBO-ICT, Hogeschool Windesheim
**Vak:** Machine Learning

## Onderzoeksvraag

In hoeverre kan de ernst van verkeersongevallen (*Slight*, *Serious* of *Fatal*) in de UK voorspeld worden op basis van omgevings- en wegkenmerken met behulp van Machine Learning?

## Setup

### 1. Dataset downloaden

De dataset is te groot voor GitHub en moet handmatig gedownload worden, alle datasets zijn te groot voor GitHub:

1. Ga naar [UK Road Safety: Accidents and Vehicles](https://www.kaggle.com/datasets/tsiaras/uk-road-safety-accidents-and-vehicles) op Kaggle.
2. Download de dataset en plaats het bestand `Accident_Information.csv` in de map `data/`.

De mapstructuur hoort er daarna zo uit te zien:

```
project/
├── data/
│   └── Accident_Information.csv
├── EDA.ipynb
├── logistische_regressie.ipynb
├── ...
└── README.md
```

### 2. EDA uitvoeren

Run eerst de **EDA notebook** (`EDA.ipynb`) volledig. Deze verwerkt de ruwe data en genereert de volgende bestanden die de modelnotebooks nodig hebben:

- `train_set.csv`
- `validation_set.csv`
- `test_set.csv`
- `y_train.csv`
- `y_val.csv`
- `y_test.csv`

### 3. Modellen draaien

Nadat de EDA is uitgevoerd kun je de modelnotebooks runnen, zoals `logistische_regressie.ipynb`.

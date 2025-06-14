# Predicció de la freqüència cardíaca en entrenaments de ciclisme

Aquest projecte forma part del Treball de Fi de Grau (TFG) i té com a objectiu desenvolupar i comparar diferents models de Machine Learning per predir la freqüència cardíaca durant entrenaments de ciclisme utilitzant dades reals d'activitats esportives.

## Objectiu

L'objectiu principal és desenvolupar models que permetin predir la freqüència cardíaca (`heart_rate`) d'un esportista a partir de dades recollides durant sessions de ciclisme. Les variables d'entrada utilitzades són:

- `power` (potència)
- `cadence` (cadència)
- `rolling_ave_alt` (altitud mitjana mòbil)
- `heart_rate` (freqüència cardíaca, com a target)

Les dades s'obtenen de fitxers `.csv` provinents de dispositius de monitorització d'entrenaments ciclistes.

## Tecnologies i llibreries

El projecte està desenvolupat en Python i fa ús, entre d'altres, de les següents llibreries:

- [Keras](https://keras.io/) i [TensorFlow](https://www.tensorflow.org/) per la creació i entrenament de models de deep learning.
- [NumPy](https://numpy.org/) i [Pandas](https://pandas.pydata.org/) per al processament i manipulació de dades.
- [Matplotlib](https://matplotlib.org/) per la visualització i generació de gràfics.

## Estructura del projecte

El projecte s'organitza en dos grans blocs:

### 1. Anàlisi exploratòria de dades (EDA) i model naïve

- Exploració i neteja de les dades.
- Visualització gràfica de les variables principals.
- Matriu de correlacions per entendre la relació entre variables.
- Creació d’un model naïve bàsic com a benchmark inicial.

### 2. Models de deep learning

S'implementen i s'avaluen tres tipus de models:

- **Multi-Layer Perceptron (MLP)**
- **Recurrent Neural Network (RNN)**
- **Long-Short Term Memory (LSTM)**

Per cada model es detalla la construcció, entrenament, i avaluació dels resultats.

## Autor

Albert Moya Nadal — [GitHub](https://github.com/albertmoyanadal)

---

*TFG - Grau en Matemàtiques*  
*Universitat de les Illes Balears*  
*2025*




# Predicció de la Freqüència Cardíaca en Entrenaments de Ciclisme

Aquest projecte forma part del Treball de Fi de Grau (TFG) i té com a objectiu desenvolupar i comparar diferents models de Machine Learning per predir la freqüència cardíaca durant entrenaments de ciclisme utilitzant dades reals d'activitats esportives.

## Descripció

La predicció de la freqüència cardíaca és una eina valuosa per a ciclistes i entrenadors, ja que permet optimitzar entrenaments, prevenir sobreentrenament i millorar el rendiment esportiu. En aquest projecte s'han implementat i comparat diversos models de predicció automàtica de la freqüència cardíaca:

- **MLP (Multi-Layer Perceptron):** Un perceptró multicapa bàsic per a la predicció seqüencial.
- **Xarxes Neuronals Recurrents (RNN):** Per capturar la dependència temporal inherent en les dades d'entrenament.
- **LSTM (Long Short-Term Memory):** Un tipus avançat de RNN que millora la capacitat de recordar patrons temporals a llarg termini.

## Objectius

- Analitzar i pre-processar dades d'entrenaments de ciclisme.
- Implementar diferents arquitectures de xarxes neuronals per a la predicció de la freqüència cardíaca.
- Avaluar i comparar el rendiment dels models utilitzant mètriques específiques.

## Estructura del Projecte

- `data/` — Dades d'entrenaments de ciclisme (pre-processades i/o brutes).
- `models/` — Implementacions dels diferents models de ML (MLP, RNN, LSTM).
- `notebooks/` — Jupyter notebooks per a l'anàlisi exploratòria, entrenament i visualització de resultats.
- `src/` — Codi font auxiliar per a pre-processament, entrenament, i avaluació.
- `results/` — Resultats de les proves i comparació de models.

## Requisits

- Python 3.8+
- Llibreries principals: `numpy`, `pandas`, `scikit-learn`, `tensorflow` / `keras`, `matplotlib`

## Autor

Albert Moya Nadal — [GitHub](https://github.com/albertmoyanadal)

---

*TFG - Grau en Matemàtiques*  
*Universitat de les Illes Balears*  
*2025*

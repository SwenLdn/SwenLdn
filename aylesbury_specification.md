# Spezifikationsdokument: SpektralPhasenModell (Wright-Fisher-Markov-Ketten)

Dieses Dokument spezifiziert das mathematische und biopolitische Modell zur Analyse der transienten Dynamik, der Spektrallücke ($\Delta \lambda$), der Relaxationszeit ($	au$) und des Systemverhaltens der Aylesbury-Kohorten (SE17/SE1) über drei historische Phasen.

## 1. Mathematisches Fundament
Die Dynamik basiert auf einer Wright-Fisher-Markov-Kette mit einer effektiven Populationsgröße $N_e$ und einer Migrationsrate $m$ aus einem unendlich großen globalen Genpool mit der Allelfrequenz $p_{	ext{global}} = 0.3$.

* **Erster Eigenwert (Perron-Frobenius):** $\lambda_1 = 1.0$
* **Zweiter Eigenwert (Mischer-Kopplung):** $\lambda_2 = (1 - m)(1 - rac{1}{2N_e})$ (für ergodische Systeme bei $m > 0$)
* **Transienter Eigenwert (Drift):** $\lambda_{	ext{transient}} = 1 - rac{1}{2N_e}$
* **Spektrallücke ($\Delta \lambda$):** 
  * Bei Isolation ($m = 0$): $\Delta \lambda = 1 - \lambda_{	ext{transient}}$
  * Bei Genfluss ($m > 0$): $\Delta \lambda = 1 - \lambda_2$
* **Relaxationszeit ($	au$ in Generationen):** $	au = rac{1}{\Delta \lambda}$

---

## 2. Spektrale Datenmatrix der Phasen

| Phase | Bezeichnung | Zeitraum | $N_e$ | Migration $m$ | $\lambda_1$ | $\lambda_2$ (Mischer) | $\lambda_{	ext{transient}}$ | Spektrallücke $\Delta \lambda$ | $	au$ (Gen.) | Senken | Zustand | Topologische Dynamik |
|:---:|:---|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---|:---|
| **1** | Pionierphase (Isolation) | um 1961 | 67 | 0.00% | 1.0000 | 1.0000 | 0.9925 | 0.0075 | 134.00 | 2 | Instabil (Bottleneck) | Reine Drift / Zerfall der Heterozygotie |
| **2** | Rettungswelle (Genfluss) | 1981–2011 | 1170 | 12.50% | 1.0000 | 0.8746 | 0.8742 | 0.1254 | 7.98 | 0 | Ergodisch / Stabil | Starker Genfluss / Fließgleichgewicht |
| **3** | Neoliberale Verdrängung | ab 2021 | 1012 | 0.00% | 1.0000 | 1.0000 | 0.9995 | 0.0005 | 2024.00 | 2 | Rezessiv / Fragmentiert | Künstliche Isolation / Stagnation |

---

## 3. Biopolitische Schlussfolgerungen
* **Phase 1 (Anfängliche Isolation):** Akute Gefährdung durch stochastische Drift und Inzucht-Senken.
* **Phase 2 (Ergodische Rettung):** Ein starker Genfluss von $m = 12.5\%$ öffnete die Spektrallücke drastisch auf $0.1254$ und stabilisierte die evolutionäre Dynamik über der kritischen Schwelle ($N_e > 500$).
* **Phase 3 (Neoliberale Fragmentierung):** Der vollständige Verlust des Genflusses bricht die Spektrallücke um das **250-Fache** auf $0.0005$ ein. Die theoretische Relaxationszeit explodiert auf $	au = 2024$ Generationen, was zu einer vollständigen biologischen und räumlichen Stagnation führt.
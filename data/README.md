# Veri

Orijinal veri: [BETH Dataset (Highnam vd., 2021), Kaggle](https://www.kaggle.com/datasets/katehighnam/beth-dataset). Bir honeypot sunucusunda kaydedilmiş 8 milyondan fazla kernel seviyesi süreç olayı; `sus` (şüpheli) ve `evil` (saldırgan) etiketli.

Repoda resmi ayrımlardan tekrar üretilebilir örnekler var (seed 42):

| Dosya | Satır | Kaynak |
|---|---|---|
| `beth_training_sample.csv` | 40.000 | `labelled_training_data.csv` |
| `beth_validation_sample.csv` | 12.000 | `labelled_validation_data.csv` |
| `beth_testing_sample.csv` | 12.000 | `labelled_testing_data.csv` |

Eğitim ve validation'da saldırı (`evil`) yok; test setinin %83.7'si saldırı. Model saldırı görmeden eğitilir.

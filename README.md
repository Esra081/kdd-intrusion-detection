# 🛡️ KDD Cup — Network Intrusion Detection

KDD Cup 1999 veri seti kullanılarak ağ saldırısı tespiti (intrusion detection) üzerine geliştirilmiş veri madenciliği projesi.

## 📊 Veri Seti

**KDD Cup 1999 / NSL-KDD** — Ağ trafiği özelliklerini içeren, saldırı ve normal trafik etiketlenmiş benchmark veri seti.

Saldırı kategorileri:
- DoS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)

## 📓 İçerik

`prohe.ipynb` notebook'u şunları içerir:
- Veri keşfi (EDA)
- Özellik mühendisliği
- Sınıflandırma modelleri (KNN, Decision Tree, Random Forest vb.)
- Model değerlendirme metrikleri

## 🚀 Kullanım

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook prohe.ipynb
```

> **Not:** KDD veri setleri büyük boyutlu olduğundan repoya dahil edilmemiştir.
> [NSL-KDD veri setini buradan indirin](https://www.unb.ca/cic/datasets/nsl.html)

## 🔧 Teknolojiler

- Python, Jupyter Notebook
- Scikit-learn, Pandas, NumPy
- Matplotlib, Seaborn

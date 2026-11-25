# SHAP Uygulama & Müşteri Sunum Rehberi

Makine öğrenmesi modellerini müşteriye ve yöneticilere metriklerle (`ROC-AUC`, `RMSE`, `F1`) değil, net iş kararlarıyla anlatmak için hazırlanmış interaktif açık kaynak rehber.

**Canlı Sayfa (GitHub Pages):** `https://mehmetbugrakara.github.io/shap-rehberi/`

## İçerik

- **SHAP Temel Mantığı:** Oyun teorisi (Shapley değeri), temel denklem ve klasik feature importance farkı.
- **İnteraktif SHAP Waterfall Simülatörü:** Müşteri churn senaryosunda canlı değişken kaydırıcıları, baz tahminden nihai tahmine etki grafiği ve otomatik iş aksiyonu.
- **Grafik Seçim Kılavuzu:** Waterfall, Beeswarm, Global Bar ve Dependence grafiklerinin kullanım senaryoları.
- **Uygulamalı Python Kodları:** Modern `shap.Explanation` API, `TreeExplainer(..., model_output="probability")` ve CRM/satış ekibi için müşteri bazlı Top-3 neden çıkarma fonksiyonu.
- **Müşteri Sunum Şablonu:** 3 slaytlık yönetici sunum iskeleti ve kopyalanabilir e-posta/özet metni.
- **5 Kritik Hata:** Nedensellik tuzağı, çoklu doğrusallık, log-odds birimi, ham kolon isimleri ve background veri seçimi.

## GitHub Pages'te Yayınlama

```bash
cd shap-rehberi
git init
git add .
git commit -m "Initial SHAP guide for GitHub Pages"
git branch -M main
git remote add origin https://github.com/mehmetbugrakara/shap-rehberi.git
git push -u origin main
```

Ardından GitHub repo ayarlarından **Settings → Pages → Source: Deploy from a branch (`main` / `/root`)** seçin. Sayfa 1-2 dakika içinde `https://mehmetbugrakara.github.io/shap-rehberi/` adresinde yayına alınır.

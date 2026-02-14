# SupervisedLearningProject
# Bank Marketing - Mevduat Tahmin Modeli
## Proje Amacı

Bu projede, müşterilerin vadeli mevduata (deposit) abone olup olmayacağını tahmin etmek amaçlanmıştır. Veri seti olarak Kaggle’daki Bank Marketing Dataset kullanılmıştır.

## Yapılan Çalışmalar

Keşifsel Veri Analizi (EDA)

Leakage içeren değişkenlerin çıkarılması (duration, campaign)

pdays değişkeninin redundant olduğu düşünülerek çıkarılması

Kategorik değişkenlere One-Hot Encoding uygulanması

Train/Test split (%80 / %20)

## Denenen Modeller

Random Forest

Logistic Regression

Logistic Regression (class_weight='balanced')

## Son Model

Balanced Logistic Regression modeli tercih edilmiştir.

## Sonuçlar:

Accuracy ≈ 0.71

ROC-AUC ≈ 0.77

Precision ve Recall dengesi daha uygun bulunmuştur.

## Önemli Bulgular

Önceki kampanya başarısı en güçlü belirleyicidir.

Housing loan sahibi olan müşterilerin kabul oranı daha düşüktür.

Contact türü önemli bir etkendir.

Geçmiş kampanya etkileşimi olumlu etki göstermektedir.

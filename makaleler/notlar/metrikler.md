# Performans metrikleri
aşağıdaki sayılar hangi metriğin hangi makalede kullanıldığını referans edecek
## 1 -> Türkçe Dil Modellerinin Performans Kar¸sıla¸stırması Performance Comparison of Turkish Language Models
## 2 -> Introducing cosmosGPT: Monolingual Training for Turkish Language Models
## 3 -> TURNA: A Turkish Encoder-Decoder Language Model for Enhanced Understanding and Generation
## 4 -> Comparison of Pre-trained Models for Optimized Transformer Based Question Answering System
## 5 -> Automated question generation and question answering from Turkish texts
### Metrikler (Otomatik Değerlendirme)

* ROUGE-1 **-> 1,2,3**
* ROUGE2 **-> 1,2,3**
* ROUGE-L **-> 1,2,3,5** 
* Precision **-> 3**
* Recall **-> 3**
* F1 **-> 3,4,5**
* Accuracy **-> 3**
* BLEU **-> 3,5**
* METEOR **-> 3**
* Exact Match **-> 4,5**
### Metrikler (İnsan değerlendirmesi)
Oylama işleminde standart sapma ve korelasyon bilgisi verilmiş.

* Elo **-> 1,2**
* WinPct -**> 1,2**

### Neden Fine Tune gerekli?



Birçok dili destekleyen modellerin Türkçe için talimat veri
kümeleriyle egitim i¸slemi öncesinde standart bir ön e ˘ gitime ˘
devam edilmesi gerektigi görülmektedir. Trendyol-chat model- ˘
linin, Trendyol-base modeline kar¸sı oylama ve rouge skorlarınca üstünlük saglamasından bu sonuca varılmı¸stır. Openchat ˘
modelinde Türkçe özelinde bir egitim yapılmamı¸s, buna kar¸sın ˘
model Trendyol-chat ile yakın sonuçlar elde etmi¸stir. **-> 1**



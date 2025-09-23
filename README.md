# Emotion-Detection-From-Image

Bu projede, Conventional Neural Networks (CNN) kullanarak Deep Learning tekniği uyguladım.
Kullandığım veri seti 48x48 grayscale ortalanmış ve sınıflandırılmış yüz resimlerinden oluşuyordu.

Sınıflar 7 farklı duygusal ifadeyi temsil ediyor: sinir, iğrenme, korku, mutluluk, doğal yüz ifadesi,üzgünlük,şaşırma.
29.000 civarı resim içeren bu veri setinde dağılım eşit değildi, bu yüzden **confusion matrixte bazı etiketlerin diğerlerine göre daha iyi ayırt edildiği görülebiliyor**, örneğin mutluluk ifadesi,
iğrenme ifadesine karşılık yaklaşık **17 kat** daha fazla veri içeriyor.

Veri Setinine ait "Data Card" : https://www.kaggle.com/datasets/msambare/fer2013

Kaggle notebook: https://www.kaggle.com/code/iskender1222421/emotion-classifier-cnn

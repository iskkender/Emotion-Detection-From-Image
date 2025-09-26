# Emotion-Detection-From-Image

Bu projede, Conventional Neural Networks (CNN) kullanarak Deep Learning tekniği uyguladım.
Kullandığım veri seti 48x48 grayscale ortalanmış ve sınıflandırılmış yüz resimlerinden oluşuyordu.

Sınıflar 7 farklı duygusal ifadeyi temsil ediyor: sinir, iğrenme, korku, mutluluk, doğal yüz ifadesi,üzgünlük,şaşırma.
29.000 civarı resim içeren bu veri setinde dağılım eşit değildi, bu yüzden **confusion matrixte bazı etiketlerin diğerlerine göre daha iyi ayırt edildiği görülebiliyor**, örneğin mutluluk ifadesi,
iğrenme ifadesine karşılık yaklaşık **17 kat** daha fazla veri içeriyor.
 <img width="652" height="513" alt="image" src="https://github.com/user-attachments/assets/99a7aa32-bf84-4656-b486-688f809c1b19" />

 Modele ait loss ve accuracy grafikleri:
 <img width="965" height="401" alt="image" src="https://github.com/user-attachments/assets/f8c80b97-3dca-4bbf-b4ad-76bf8a30528d" />



Veri setine ait Data Card : https://www.kaggle.com/datasets/msambare/fer2013

Kaggle notebook: https://www.kaggle.com/code/iskender1222421/emotion-classifier-cnn

# Multilayer-Perceptron-MLP-Example

(Hikaye dosyalarda ekli)

İki hidden layer'lı bir Multilayer Perceptron (MLP) oluşturacağız.
Hazır aktivasyon fonksiyonlarını kullanmak serbest. İlk hidden layer'da 100, ikinci hidden layer'da 50 nöron olsun. 
Hidden layer'larda ReLU, output layer'da sigmoid aktivasyonu olsun.

Output layer'da 2 nöron olacak. veriye uygun Cross Entropy loss yöntemini uygulayacağız. 
Optimizasyon için Stochastic Gradient Descent 
Epoch sayınızı ve learning rate'i validasyon seti üzerinde denemeler yaparak (loss'lara overfit var mı diye bakarak) kendiniz belirleyeceğiz. 
Batch size'ımız 16 
[Multilayer Perceptron (MLP) Saving The Princess_1]


SEED= 190401064 set ettikten sonra 
training batch'lerinden eğitim loss'ları, validation batch'lerinden validasyon loss değerlerini 
hesaplayan kod [Multilayer Perceptron (MLP) Saving The Princess_2]

SEED=190401064 set ettikten sonra 
earlystopping'deki en iyi modeli kullanarak, 
Prensesi İyileştir test setinden accuracy, F1, precision ve recall değerlerini hesaplayan kod [Multilayer Perceptron (MLP) Saving The Princess_2]

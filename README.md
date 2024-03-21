# Profanity Detection with Text

## Proje Hakkında
Bu proje, metin içerisinde küfür veya uygunsuz ifadeleri tespit etmek amacıyla geliştirilmiş bir Python uygulamasıdır. Makine öğrenimi tekniklerinden yararlanarak, verilen bir metin dizisinde küfür içerip içermediğini belirleyebilir. Proje, eğitim ve tahmin olmak üzere iki ana bileşenden oluşur.

## Başlarken

### Önkoşullar
Projeyi yerel makinenizde çalıştırmak için Python'un yüklü olması gerekmektedir. Ayrıca, projede kullanılan kütüphaneleri yüklemek için aşağıdaki `pip` komutunu kullanabilirsiniz:


### Kurulum
Projeyi yerel makinenize klonlayın:

git clone https://github.com/samedakgun/Profanity-Detection-with-text.git

Klonlama işlemi tamamlandıktan sonra, proje dizinine gidin ve gerekli Python kütüphanelerini `requirements.txt` dosyasını kullanarak yükleyin.

## Kullanım
Projeyi kullanmak için öncelikle modeli eğitmeniz gerekmektedir. Bunun için aşağıdaki komutu çalıştırın:

python src/train_model.py


Model eğitimi tamamlandıktan sonra, metin üzerinde küfür tespiti yapmak için `predict.py` script'ini çalıştırabilirsiniz:

python src/predict.py


Kullanıcıdan metin girişi aldıktan sonra, script metinde küfür olup olmadığını kontrol eder ve sonucu ekrana yazdırır.

## Katkıda Bulunma
Projeye katkıda bulunmak isteyenler için pull request'ler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak üzere bir konu açınız.

## İletişim
Samed Akgun - [@LinkedIn](https://www.https://www.linkedin.com/in/abdussamed-akg%C3%BCn-5b68141b9/)

Proje Linki: [https://github.com/samedakgun/Profanity-Detection-with-text](https://github.com/samedakgun/Profanity-Detection-with-text)

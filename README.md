# Object_Detection
 Sheep-Detection-YOLOv3-416

https://pjreddie.com/darknet/yolo/ linkinden YOLOv3-416'nın 
weights dosyasını indirin ve model klasörü içerisine çıkartın.


Anaconda Spyder IDE' si ile gerçeklenmiştir.



Eğitimi google colab aracılığıyla gerçekleştirdim.

Kılavuz olarak https://pysource.com/2020/04/02/train-yolo-to-detect-a-custom-object-online-with-free-gpu/ kullandım.

Train dosyalarını Kaggle'ın dataset dosyalarından (https://www.kaggle.com/search?q=sheep) topladım ve LabelImg (https://github.com/tzutalin/labelImg#installation) aracılığı ile etiket dosyalarımı oluşturdum.

Oluşan eğitim dosyaları ve imgeleri images.zip adı ile zip dosyasına dönüştürdüm ve yolov3 klasörü adı ile drive'a yükledim. Ardından Colaboratory dosyamda ki kodu çalıştırdım ve Drive'ımda oluşan ağırlık dosyalarımı oluşturduğum spyder projeme ekledim(cfg dosyalarımızı yolo'nun https://pjreddie.com/darknet/yolo/ linkinden elde edebilirsiniz) ve my_model isimli python dosyamda çalıştırdım. 



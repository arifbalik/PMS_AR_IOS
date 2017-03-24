# PMS_AR_IOS

OpenCV uzerinde kurabilecegimiz uygun seylerden biri SURF (http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_feature2d/py_surf_intro/py_surf_intro.html) digeri de Haar Cascade Classification (http://docs.opencv.org/2.4/modules/objdetect/doc/cascade_classification.html) 

SURF herseyi real-time olarak  yatigi icin biraz yavas kaliyor. Fakat eger tarama isi onceden bulutta yapilirsa daha rahat olur diyorlar (alttaki SURF ile ilgili kitapta). Haar ise onceden makinanin training surecinden gecip bir .xml ciktisi olusturmasi, tum detection isini de ona gore yapmasi ile ilgili. Training isi cok zaman aliyor ama eger basarili bir sekilde olursa makinayi hic kasmadan cok temiz bir sekilde calisiyor.

Not : Standart opencv ios frameworkleri ile SURF calistiramiyorsunuz cunku bazi kutuphaneler eksik. Repoda ek modullerle derlenmis bir versiyonunu koydum. Bu frameworku icinde xfeatures2d ile compile ettim.

Linkler;

Traning oepncv for a spesicific object http://coding-robin.de/2013/07/22/train-your-own-opencv-haar-classifier.html

A book about SURF with IOS https://www.safaribooksonline.com/library/view/ios-application-development/9781785289491/ch05s12.html

Toptal's blog : https://www.toptal.com/machine-learning/real-time-object-detection-using-mser-in-ios



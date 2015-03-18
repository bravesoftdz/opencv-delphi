J'ai mis ce code pour implémenter OpenCV avec Delphi

Version OpenCV: 2.3

Version Delphi 7 (j'ai pas encore testé avec Delphi 8, ....XE2)

Contenu du fichier
> - Les fichiers binaire ".dll" OpenCV 2.3

> - Les fichiers entêtes ".pas" contenant les fonctions et procédures
    * OpenCV\_Core.pas
    * OpenCV\_ImgProc.pas
    * OpenCV\_Legacy.pas
    * OpenCV\_HighGui.pas
    * OpenCV\_Types.pas
    * OpenCV\_Utils.pas
    * OpenCV\_MachineLearning.pas
    * OpenCV\_GPU.pas
    * OpenCV\_Features.pas
    * OpenCV\_ObjDetect.pas
    * OpenCV\_Video.pas
    * OpenCV\_Calibration.pas

> - Les Examples démontrant l'utilisation en delphi.
> > J'ai mis des examples juste pour demontrer que ça marche parfaitement.
Cette example n'est pas parfait mais il fonctionne.
    * ANPR
    * BackGround Substraction
    * Canny
    * Compare Histogram
    * Drawing Histogram
    * Find Object
    * Machine Learning (KNearest)
    * Match Template
    * Motion Detection
    * OCR
    * Segmentation (Sobel, Laplace, ....)
    * Snake
    * Threshold
    * Track Corner
    * Tracking Face, Mouth, Eye

D'autre probleme que j'ai rencontrer c'est d'utiliser les class C++ en delphi, donc j'ai trouver une solution de créer une fichier OpenCV\_Class.dll pour faire l'interface sur les class C++.

D'autre probleme aussi d'utiliser les fonction GPU en delphi. Je sais pas comment on convertit les templates <> en delphi.


> Si vous trouver d'autre amélioration, envoie moi au rdr2510@gmail.com
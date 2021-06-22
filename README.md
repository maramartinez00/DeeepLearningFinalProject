# DeeepLearningFinalProject
El codigo adjunto nos permitirá generar melodias de piano entrenando previamente diferentes bases de datos (con archivos midi) en una RNN.


El notebook musicGeneration.ipynb es el archivo que permite entrenar nuestra red a partir de un dataset y generar melodias.

El notebook musicGenerationAndTransfer.ipynb es el archivo que nos permite realizar el transfer. Funciona practicamente igual que el notebook anterior pero añade esta nueva funcionalidad.


La carpeta Results contiene los resultados obtenidos de las diferentes pruevas:
  - transfer_muse_chorales01.mid --> transfer learning con datasets MuseData y JSB ReducedChorales
  - nottingham01.mid --> train con Nottigham y temperatura 0.9
  - nottingham02.mid --> train con Nottingham y temperatura 0.2
  - nottingham03.mid --> train con Nottingham y 10 epochs
  - nottingham04.mid --> train con Nottingham y 1 epoch
  - musereduced01.mid --> train con MuseReduced
  - Muse100Epoc.mid --> train con MuseData y 100 epochs
  - muse01.mid --> train con MuseData y 10 epochs
  - muse02.mid --> train con Musedata
  - ChoralesReduced01.mid --> train con JSB ReducedChorales
  - chorales01.mid --> train con JSB Chorales

Los archivos de los cuales no se especifica la temperatura, entendemos que T=0.7 y si no especifica epochs, entendemos que epochs = 2.


La carpeta midi contiene arxivos python necesarios para la ejecución del codigo principal. Los archivos dee esta carpeta no se deben modificar.

El archivo zip DS contiene los datasets utilizados.

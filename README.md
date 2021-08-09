# MMF-VQA
Este repositorio contiene los notebooks referentes al módulo de implementación y uso de "Multimodal Deep Learning Models" en problemas complejos de AI. Este curso es impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/)

En este repositorio se implementa la librería MMF para poder analizar una imagen y responder preguntas abiertas. Se utilizan diferentes modelos pre-entrenados que contiene el Zoo de MMF; como Pythia, VocabProcessor, VQAAnswerProcessor así como el Dectron2 para análisis y extracción de features de imágenes. 

La implementación se hizo en Python, en un Jupyter Notebook usando Pytorch, Torchvision, MMF. Debido a que es necesario o más práctico entrenar e implementar estos modelos usando CUDAs. Se probó y se pensó en la ejecución usando Google Colab. Dentro del notebook está contemplado un ejemplo de como usar y el resultado que obtendremos del modelo. Por razones de entrenamiento es necesario realizar las preguntas en inglés. 

El código está dividido en instalación, configuración y una clase que contiene lo necesario para compilar un demo. De igual modo se provee con un demo práctico del uso y de la respuesta de dicho modelo

Para la implementación se han usado principalmente las siguientes referencias 

[1] Singh, Amanpreet and Goswami, Vedanuj and Natarajan, Vivek and Jiang, Yu and Chen, Xinlei and Shah, Meet and Rohrbach, Marcus and Batra, Dhruv and Parikh, Devi, "MMF: A multimodal framework for vision and language research", 2020, [MMF](https://github.com/facebookresearch/mmf)

[2] Casey Fitzpatrick, "HOW TO BUILD A MULTIMODAL DEEP LEARNING MODEL TO DETECT HATEFUL MEMES", TUE 12 MAY 2020, [Hateful Memes Benchmark](https://www.drivendata.co/blog/hateful-memes-benchmark/)

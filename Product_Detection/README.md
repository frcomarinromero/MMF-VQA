## Uso

### Scripts de predicción y entrenamiento del modelo unimodal

1. resnet50_train_predict.ipynb : Ajuste el modelo Resnext50 previamente entrenado en imágenes de Rakuten

2. camembert_train_predict.ipynb : Fine-tune el modelo Cammebert previamente entrenado en texto en francés; Modelo Cammbert personalizado con salida vectorial (utilizado más tarde para la fusión de características)

3. flaubert_train_predict.ipynb : Fine-tine el modelo Flaubert previamente entrenado en texto en francés; Modelo Flaubert personalizado con salida vectorial (usado más tarde para la fusión de características)

### Fusión de nivel de característica multimodal
1. multi_modal_concatenate_fusion.ipynb : Concatenar las características extraídas y entrenar el módulo NN en la parte superior

### Fusión de niveles de probabilidad
1. boosted_late_fusion.ipynb : Entrenar modelo LightGBM con probabilidad de clase como entrada

### Fuentes
https://challengedata.ens.fr/challenges/35
https://sigir-ecom.github.io/data-task.html
https://arxiv.org/abs/2104.09423



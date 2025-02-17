# Deep-Learning---Proyecto

## Indicaciones Generales
17/02/2025: ResNet18_Dropout_Soft_Attention_Model.ipynb es el archivo de ejecucion principal

Para la visualización del entrenamiento y sus gráficas en navegador, ejecutar el siguiente comando:
``` powershell
tensorboard --logdir=runs
```

## Instalación de librerías
Instalar el ambiente virtual de python:
``` powershell
python -m venv venv
```

Instalar manualmente la version de pytorch acorde a la version cuda instalada:
https://pytorch.org/get-started/locally/

Activar el ambiente virtual para la consola:
``` powershell
./venv/Scripts/Activate.ps1
```

Instalar librerías (ubicadas en requirements.txt):
``` python
pip install -r ./requirements.txt
```

## Estructura de archivos
content/GPTeam-DeepLearning/Dataset/        ->      Contiene los archivos a ser leidos
saved_parameters/                           ->      Contiene los modelos y pesos de la red neuronal guardados, contiene los directorios Models y Parameters, ellos guardaran las arquitecturas del modelo y los pesos, correspondientemente.
runs/                                       ->      Contiene los archivos generados por tensorbord para visualizar las ejecuciones
results/                                    ->      Contiene los resultados generados por las ejecuciones de cada época


## Gráficos realizados
- [X] Gráfica Loss 
- [X] Gráfica Accuracy 
- [X] Heatmap de predicciones
- [X] Heatmap de TP, FP, TN, FN
- [ ] Curva ROC
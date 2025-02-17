# Deep-Learning---Proyecto

17/02/2025: ResNet18_Dropout_Soft_Attention_Model.ipynb es el archivo de ejecucion principal

Instalar el ambiente virtual de python:
python -m venv venv

Instalar manualmente la version de pytorch acorde a la version cuda instalada:
https://pytorch.org/get-started/locally/

Activar el ambiente virtual para la consola:
./venv/Scripts/Activate.ps1

Instalar librerías (ubicadas en requirements.txt):
pip install -r ./requirements.txt

# Estructura de archivos
content/GPTeam-DeepLearning/Dataset/        ->      Contiene los archivos a ser leidos
saved_parameters/                           ->      Contiene los modelos y pesos de la red neuronal guardados, contiene los directorios Models y Parameters, ellos guardaran las arquitecturas del modelo y los pesos, correspondientemente.
runs/                                       ->      Contiene los archivos generados por tensorbord para visualizar las ejecuciones
results/                                    ->      Contiene los resultados generados por las ejecuciones de cada época

# Visualizacion de Tensorboard en navegador
Ejecutar desde terminal la siguiente instrucción:
tensorboard --logdir=runs
# BayesianLSTM

Los modelos de Redes Neuronales Recurrentes (RNN) se han propuesto como solución a diversos problemas de series de tiempo, sin embargo, a pesar de realizar pronósticos 
acertados carecen de una medida de la incertidumbre. Recientemente, los modelos de Redes Neuronales Bayesianos han ganado popularidad como el principal medio para conseguir 
una estimación del error en modelos de Deep Learning. Haremos uso de datos de generación de energía eólica horaria en España, entre 2014-2019, aplicando la metodología del 
Dropout de Montecarlo para realizar un pronóstico de un paso adelante dando una estimación de la incertidumbre de un modelo de Redes Neuronales LSTM.

Aquí encontrarás:

- Código para descarga de ficheros de la Red Eléctrica de España (REE), utilizando la librería Selenium de Python.
- Código del modelo LSTM Bayesiano propuesto, escrito en Keras.
- Bibliografía.

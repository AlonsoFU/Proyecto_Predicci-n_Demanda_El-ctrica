# Proyecto_Prediccion_Demanda_El-ctrica


El código a continuación corresponde a la predicción de una semana de demanda de energía (Retiro de energía MWh) de una barra del Sistema Nacional Chileno en un periodo en especifico, a partir de parámetros ambientales, retiros de energías correspondientes a la misma hora de semanas anteriores, tipo de día, día de la semana, entre otras. El listado de variables se puede ver a continuación:

Año: Año de la demanda Ts_Valor: Temperatura de la comuna Retiro suma MWh: Energía demandada en la central semana actual Retiro suma MWh hace 1 semana promedio: Energía demandada promedio de la semana actual Hora: Hora de la demanda HR_Valor: Humedad Td_Valor: Punto Rocio dd_Valor: Dirección del viento ff_Valor: Rápidez de viento VRB_Valor: Viento de dirección Variable

Por otro lado, se compara los resultados del mejor modelo de machine learning utilizado (SVM) con el mejor modelo de red neuronal utilizado (basado en LSTM)

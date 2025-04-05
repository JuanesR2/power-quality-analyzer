# Power Quality Analyzer 🔌📈

Este repositorio analiza señales de tensión para evaluar la calidad de energía usando Python. Calcula el THD, muestra el espectro de frecuencia y permite entender los armónicos presentes.

## Funcionalidades

- Carga de datos desde archivos `.csv`
- Análisis de frecuencia usando FFT
- Cálculo del Total Harmonic Distortion (THD)
- Visualización del espectro de armónicos

## Requisitos

- pandas
- numpy
- matplotlib
- scipy

## Cómo usar

1. Coloca tu archivo `waveform.csv` en el mismo directorio.
2. Ejecuta el script:

```bash
python main.py

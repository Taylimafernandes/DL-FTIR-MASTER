

# DL-FTIR-MASTER

Este repositório compila a simulação computacional desenvolvida para a tese de Mestrado intitulada: Caracterização de materiais utilizando Deep Learning via Espectroscopia de FT-IR.

---

## Resumo da Pesquisa

**Título:** Caracterização de materiais utilizando Deep Learning via Espectroscopia de FT-IR

**Objetivo:**
Desenvolver e avaliar uma abordagem utilizando modelos de deep learning para a classificação automática de espectros obtidos por espectroscopia no infravermelho por transformada de Fourier (FTIR), visando identificar padrões e auxiliar em diagnósticos rápidos e precisos.

**Contexto:**
A espectroscopia FTIR é uma técnica amplamente utilizada para análise de compostos químicos e biológicos. A aplicação de inteligência artificial, especialmente redes neurais profundas, permite extrair informações relevantes de grandes volumes de dados espectrais, superando limitações de métodos tradicionais.

**Base de Dados:**
Os dados utilizados consistem em espectros FTIR coletados de amostras biológicas, organizados e processados nos notebooks deste repositório. O pipeline inclui extração, validação, pré-processamento (normalização, remoção de ruído, etc.) e divisão em conjuntos de treino/teste.

**Metodologia:**
- Pré-processamento dos espectros (normalização, filtragem, etc.)
- Implementação e comparação de diferentes arquiteturas de deep learning:
	- MLP (Perceptron Multicamadas)
	- LSTM (Long Short-Term Memory)
	- GRU (Gated Recurrent Unit)
	- Autoencoders
	- Redes Convolucionais 1D e 2D (CONV1D, CONV2D)
- Otimização de hiperparâmetros com Optuna
- Avaliação dos modelos por métricas como acurácia, precisão, recall, F1-score e análise das curvas de aprendizado. Métrica central Hamming Loss.
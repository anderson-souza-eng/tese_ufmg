# Tese UFMG: Enhancing Machine Learning Models to Evaluate Optical Water Quality Parameters of Reservoirs Through Remote Sensing Data
Este repositório contempla alguns dos códigos-fonte exemplificativos dos métodos desenvolvidos na tese  "Enhancing Machine Learning Models to Evaluate Optical Water Quality Parameters of Reservoirs Through Remote Sensing Data" (http://hdl.handle.net/1843/81290).
- Citação: de Souza, A. P. (2024). Enhancing machine learning models to evaluate optical water quality parameters of reservoirs through remote sensing data.

A tese de doutorado foi desenvolvida junto ao projeto “Monitoramento Inteligente da Qualidade da Água em Reservatórios Hidrelétricos Através do Desenvolvimento de um Algoritmo Fotogramétrico” — parceria entre CEMIG e UFMG — que criou o ambiente ideal para o desenvolvimento da tese (UFMG, 2020–2024).

O estudo concentrou-se no aprimoramento de técnicas de ML para avaliação de parâmetros ópticos de qualidade da água em reservatórios, com ênfase em: (i) modelos de regressão para estimativa de concentração de parâmetros; (ii) detecção de anomalias em dados espectrais; (iii) adaptação de domínio para transferência de conhecimento entre reservatórios com características distintas. Como contribuições, destacam-se: (a) desenvolvimento de fluxos de processamento autoajustáveis às características ópticas dos reservatórios; (b) validação de modelos treinados em contextos heterogêneos (transferibilidade); (c) método PASS (Pre-adaptation Samples Selection), que otimiza o processamento, selecionando apenas amostras do domínio fonte semelhantes ao alvo.

A orientação foi conduzida por um time multidisciplinar de excelência, fomentando um escopo de pesquisa robusto e inovador: Prof.ª Camila Costa de Amorim (UFMG), especialista em monitoramento ambiental e ecotoxicologia; Prof. Jefersson Alex dos Santos (UFMG/Universidade de Sheffield), fundador do laboratório PATREO/UFMG, referência em visão computacional e sensoriamento remoto; e Prof.ª Mauren Sguario de Andrade (UTFPR), com expertise em processamento de imagens. 

## Códigos-fonte: #
### CaptGeo: aplicação de captura de valores de pixels das 12 bandas espectrais de imagens do Satélite Sentinel-2A, executável em ambiente Colab ou local.
- 0_Captura_Dados_Sentinel_2A_v14_01102024.ipynb

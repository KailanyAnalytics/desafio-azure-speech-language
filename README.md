# 🚀 Desafio DIO - Azure Speech e Language Studio

Este repositório documenta minha experiência prática no laboratório proposto pela DIO, com foco no uso das ferramentas **Azure Speech Studio** e **Azure Language Studio** para análise de fala e linguagem natural.

## 🎯 Objetivo

Aplicar os conceitos aprendidos durante o curso em um ambiente real, testando as capacidades da inteligência artificial da Azure para transcrever, analisar e interpretar linguagem humana.

---

## 🧪 Etapas Realizadas

### 🔊 1. Speech Studio - Transcrição de Áudio

Utilizei um áudio intitulado **"Mestrado"**, que abordava a construção de modelos de machine learning para prever o consumo de substâncias (com foco em cannabis) a partir de dados demográficos e traços de personalidade.

#### 📄 Transcrição gerada:
> Olá, hoje a nossa análise vai fundo em um tema fascinante, como é que a gente pode usar dados sobre pessoas, idade, escolaridade, até personalidade para tentar prever a chance de consumir uma droga específica. O foco hoje é cannabis. [...] (transcrição completa no repositório)

A transcrição foi altamente fiel, com excelente segmentação de frases e pontuação automática. O conteúdo do áudio detalhou desde o pré-processamento de dados até a escolha e avaliação de modelos de machine learning, incluindo técnicas como:

- Validação cruzada (K-fold)
- Modelos como regressão logística, Random Forest e XGBoost
- Métricas como acurácia, precisão, recall e matriz de confusão
- Interpretação dos resultados com base na legenda dos dados

---

### 💬 2. Language Studio - Análise de Linguagem Natural

Após a transcrição, enviei o texto ao **Language Studio** para análise de linguagem, onde foram detectadas **72 entidades (estâncias)** relevantes no conteúdo.

As entidades extraídas ajudam a identificar:

- Temas centrais (como *cannabis*, *personalidade*, *machine learning*)
- Conceitos técnicos (como *validação cruzada*, *precisão*, *classificação binária*)
- Informações demográficas e psicológicas (como *idade*, *educação*, *neuroticismo*)

Essa etapa permitiu observar o poder da IA para extrair insights semânticos complexos de textos falados.

---

## 🧠 Principais Aprendizados

- A transcrição automática da fala no Speech Studio é eficaz mesmo para conteúdos técnicos.
- O Language Studio extraiu corretamente conceitos técnicos e semânticos do conteúdo.
- Dados pré-codificados (como os do estudo original citado no áudio) eliminam a necessidade de pré-processamentos manuais, facilitando a aplicação de modelos de aprendizado de máquina.
- A reflexão sobre o equilíbrio entre a simplificação numérica dos dados humanos e a preservação de sua complexidade é crucial em projetos de IA.

---


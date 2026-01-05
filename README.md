# Classificação de Imagens de Resíduos usando Deep Learning

## 📌 Visão Geral do Projeto
Este projeto tem como foco a **classificação de diferentes variedades de trigo utilizando técnicas de machine learning**, com o objetivo de apoiar processos de separação e otimização de grãos trigo de inteligência artificial.

O estudo avalia e compara o desempenho de diferentes **arquiteturas de aprendizado de máquina** aplicadas a tarefas de classificação e otimização de dados de diferentes tipos de grão, utilizando um conjunto de dados seeds_dataset.txt.

Este projeto foi desenvolvido como parte do **Curso de Pós-Graduação em Ciência de Dados**.

---

## 🎯 Objetivos
- Aplicar técnicas de machine learning para classificar utilizando algoritmo genérico e PSO
- Comparar o desempenho de múltiplos classificadores (regressão logística, árvore de decisão e random forest)
- Avaliar os modelos por meio de métricas: Teste t, GA_FS, PSO_FS
- Verificar as melhores soluções para gestão de diferentes variedades de trigo

---

## 🧠 Modelos e Arquiteturas
As seguintes arquiteturas de machine learning pré-treinadas foram utilizadas e avaliadas:
- **RandForest**
- **LogReg**
- **DecTree**

Foram utilizadas técnicas de **Algoritmo Genético (GA)** e **Otimização por Enxame de Partículas (PSO)**  para seleção de caracteristicas do treinamento.

---

## 📂 Conjunto de Dados (Dataset)
- **Nome:** Seeds Dataset
- **Fonte:** UCI Datasets
- **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/00236/seeds_dataset.txt

O dataset contém dados de diferentes variedades de trigo separados e classificados, separados por três variedades diferentes de trigo: Kama, Rosa e Canadian, 70 elementos de cada variedade, selecionados aleatoriamente para o experimento. Sendo adequado para tarefas de classificação supervisionada.

---

## 🧪 Metodologia
1. Carregamento e pré-processamento dos dados
2. Redimensionamento e separação dos dados em treio e teste
3. Implementação dos Algoritmos Genético (DEAP) e Otimização por Enxame de Partículas (PSO) para Seleção de Características
4. Execução das Otimizações e Seleção de Características Finais
4. Avaliação dos modelos por meio de:
   - Teste t
   - GA_FS vs PSO_FS para o Random Forest (Acurácia)
   - GA_FS vs ALL para a Regressão Logística (Acurácia)
   - ALL vs PSO_FS para a Árvore de Decisão (Tempo de Treinamento)
   
5. Comparação de desempenho entre os algoritmos

---

## 📊 Métricas de Avaliação
- Acurácia
- Tempo de Treinamento


---

## 🔗 Recursos do Projeto

### 🧩 Pipeline (Git e Github)
https://github.com/marcelomanoelmiranda/projeto_feature_selection/blob/70b455c261a7555522202f4819a37c348186fbe7/projeto_final_feature_selection.ipynb


---

## 👥 Integrantes do Projeto
- **Marcelo Manoel dos Santos Miranda**
- **Flavius Raymundo Arruda Sodré**
- **Robson Florencio Correia**

---

## 🎓 Contexto Acadêmico
- **Curso:** Pós-Graduação em Ciência de Dados
- **Disciplina:** OTIMIZAÇÃO E COMPUTAÇÃO EVOLUCIONÁRIA
- **Orientador:** Prof. Adiel Filho

---

## 🚀 Como Executar o Projeto
1. Acesse o link do pipeline 
2. Conecte-se a um ambiente com GPU (recomendado)
3. Carregue o dataset a partir do Kaggle(ou outro ambiente)
4. Execute as células do notebook sequencialmente

---

## 📌 Palavras-chave
Machine Learning, RandomForest, Regressão Logística, Árvore de Decisão, Algoritmo Genético, PSO

---

## 📜 Licença
Este projeto é destinado **exclusivamente para fins acadêmicos e de pesquisa**.

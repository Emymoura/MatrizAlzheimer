<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&height=200&width=1000&color=1e3a8a&reversal=false&fontAlignY=20&text=Integração%20Multi-estudo%20Alzheimer&fontSize=32&fontColor=F8F8FF&animation=fadeIn"
    width="100%"
  />
</p>

> [!IMPORTANT]
> Este repositório contém o pipeline automatizado e reprodutível de engenharia de dados em Python para a filtragem, normalização, padronização e integração de dados de expressão gênica multi-estudo da Doença de Alzheimer[cite: 1].

## 🧠 Sobre o Projeto
O aumento exponencial da disponibilidade de dados em repositórios públicos tem motivado investigações sobre doenças complexas como a Doença de Alzheimer[cite: 1]. Contudo, diferenças nos formatos, na estrutura e na qualidade dos dados transcriptômicos obtidos por diferentes plataformas experimentais inviabilizam sua integração direta[cite: 1]. 

Este projeto integra quatro conjuntos de dados independentes (**GSE33000, GSE26927, GSE29378 e GSE37263**), disponibilizando uma base de dados unificada, limpa e pronta para análises computacionais[cite: 1].

## 📂 Estrutura do Repositório
📦 [Integracao-Dados-Alzheimer](./)

  📂 [NotebooksCode](./NotebooksCode/)
  
  ┗ 📄 [Pipeline_Integracao.ipynb](./NotebooksCode/Pipeline_Integracao.ipynb)  
 
  📂 [PythonCode](./PythonCode/)  
 
  ┗ 📄 [processamento.py](./PythonCode/processamento.py)
 
  📂 [Imagens](./Imagens/)    
 
  ┗ 🖼️ [Fluxograma.png](./Imagens/Fluxograma.png)  
 
  📄 [README.md](./README.md)

## 🔄 Fluxo Metodológico (Pipeline)

<p align="center">

<img src="https://img.shields.io/badge/Obtenção%20GEO%20/%20AlzData-1e3a8a?style=for-the-badge&logo=databricks&logoColor=white">
<br>
↓
<br>
<img src="https://img.shields.io/badge/Filtragem%20(Cobertura%20≥%2080%25)-2563eb?style=for-the-badge&logo=python&logoColor=white">
<br>
↓
<br>
<img src="https://img.shields.io/badge/Seleção%20de%20Genes%20Comuns-3b82f6?style=for-the-badge">
<br>
↓
<br>
<img src="https://img.shields.io/badge/Normalização%20Z--score-60a5fa?style=for-the-badge">
<br>
↓
<br>
<img src="https://img.shields.io/badge/Concatenação%20e%20Metadados-93c5fd?style=for-the-badge">
<br>
↓
<br>
<img src="https://img.shields.io/badge/Dataset%20Integrado%20Final-1e3a8a?style=for-the-badge&logo=pandas&logoColor=white">
<br>

</p>

## 📊 Matriz Integrada e Resultados
Após o pré-processamento e o tratamento de inconsistências, o processo resultou em uma **matriz de dados íntegra, estruturada e sem dados ausentes**[cite: 2], contendo:
* **Volume de Amostras:** 460 amostras no total, sendo 277 classificadas como Alzheimer e 183 como controles[cite: 2].
* **Atributos (Genes):** Intersecção de aproximadamente 12.085 genes comuns[cite: 2].
* **Padronização:** Expressão gênica normalizada por Z-score individualmente dentro de cada estudo[cite: 2].
* **Metadados:** Preservação de informações sobre condição clínica, idade, sexo e estudo de origem, permitindo uma comparação justa entre diferentes amostras e regiões anatômicas[cite: 2].

## 📌 Palavras-chave
Doença de Alzheimer | Expressão Gênica | Engenharia de Dados | Bioinformática[cite: 2]

## 👥 Autores
* **Emily Vitorya de Moura**

### 📬 Contato
[![Gmail](https://skillicons.dev/icons?i=gmail)](mailto:emilymoura@alunos.utfpr.edu.br)
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com/Emymoura)
[![LinkedIn](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/emily-vitorya-de-moura-ab799b273)

<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&height=200&color=1e3a8a&section=footer"
    width="100%"
  />
</p>

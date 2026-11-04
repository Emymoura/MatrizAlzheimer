<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&height=200&width=1000&color=1e3a8a&reversal=false&fontAlignY=20&text=Integração%20Multi-estudo%20Alzheimer&fontSize=44&fontColor=F8F8FF&animation=fadeIn"
    width="100%"
  />
</p>

> [!IMPORTANT]
> Este repositório contém o pipeline automatizado e reprodutível de engenharia de dados em Python para a filtragem, normalização, padronização e integração de dados de expressão gênica multi-estudo da Doença de Alzheimer.

## 🧠 Sobre o Projeto
O aumento exponencial da disponibilidade de dados em repositórios públicos tem motivado investigações sobre doenças complexas como a Doença de Alzheimer.
Contudo, diferenças nos formatos, na estrutura e na qualidade dos dados transcriptômicos obtidos por diferentes plataformas experimentais inviabilizam sua integração direta. 

Este projeto integra quatro conjuntos de dados independentes (**GSE33000, GSE26927, GSE29378 e GSE37263**), disponibilizando uma base de dados unificada, limpa e pronta para análises computacionais.

## 📂 Matriz Integrada
  📄 https://drive.google.com/file/d/1fgTVmUaIKqc6U7y-2dD7pws__175sJoj/view?usp=sharing

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
Após o pré-processamento e o tratamento de inconsistências, o processo resultou em uma **matriz de dados íntegra, estruturada e sem dados ausentes**, contendo:
* **Volume de Amostras:** 460 amostras no total, sendo 277 classificadas como Alzheimer e 183 como controles.
* **Atributos (Genes):** Intersecção de aproximadamente 12.085 genes comuns.
* **Padronização:** Expressão gênica normalizada por Z-score individualmente dentro de cada estudo.
* **Metadados:** Preservação de informações sobre condição clínica, idade, sexo e estudo de origem, permitindo uma comparação justa entre diferentes amostras e regiões anatômicas.

## 📌 Palavras-chave
Doença de Alzheimer | Expressão Gênica | Engenharia de Dados | Bioinformática

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

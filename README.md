<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&height=200&width=1000&color=1e3a8a&reversal=false&fontAlignY=20&text=Integração%20Multi-estudo%20Alzheimer&fontSize=32&fontColor=F8F8FF&animation=fadeIn"
    width="100%"
  />
</p>

> [!IMPORTANT]
> Este repositório contém o código e o pipeline automatizado de engenharia de dados desenvolvido em Python para filtragem, normalização, padronização e integração de dados de expressão gênica multi-estudo da Doença de Alzheimer[cite: 1].

## 🧠 Sobre o Projeto
O aumento exponencial da disponibilidade de dados em repositórios públicos tem motivado investigações sobre doenças complexas como a Doença de Alzheimer[cite: 1]. Contudo, diferenças nos formatos, na estrutura e na qualidade dos dados transcriptômicos obtidos por diferentes plataformas experimentais inviabilizam sua aplicação direta[cite: 1]. 

Este projeto desenvolve um pipeline robusto para unificar múltiplos datasets (GSE33000, GSE26927, GSE29378 e GSE37263), gerando uma base de dados limpa, integrada e pronta para análises estatísticas e modelos de *Machine Learning*[cite: 1, 2].

## 🛠️ Bibliotecas e Dependências
> [!NOTE]
> O projeto foi desenvolvido utilizando a linguagem Python. As principais bibliotecas utilizadas para manipulação de dados e engenharia de dados incluem:

```bash
pip install pandas
pip install numpy
pip install scikit-learn
pip install matplotlib
pip install seaborn

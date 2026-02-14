# Imersão Dados 3 — Alura

> Repositório com anotações, notebooks e desafios da 3ª edição da [Imersão Dados da Alura](https://www.alura.com.br/imersao-dados), com foco em análise de dados de Drug Discovery e primeiro modelo de Machine Learning (MoA).

[![Repositório oficial](https://img.shields.io/badge/Alura-Imersão%20Dados%203-blue)](https://github.com/alura-cursos/imersaodados3) [![Desafio final](https://img.shields.io/badge/Alura-Desafio%20Final-green)](https://github.com/alura-cursos/imersao-dados-desafio-final)

![](https://github.com/henriqueotogami/imersao-dados-3-alura/blob/main/biotechnology.jpg?raw=true)

*Photo by [Science in HD](https://unsplash.com/@scienceinhd) on [Unsplash](https://unsplash.com/s/photos/data-science)*

---

## 📋 Sobre o Projeto

Este projeto contém anotações das aulas, notebooks desenvolvidos e soluções de desafios da **3ª edição da Imersão Dados da Alura**. O objetivo é analisar uma base de dados em CSV com informações de tratamentos fármacos em células, comparando resultados de drogas e não-drogas em três intervalos de tempo (24h, 48h e 72h).

Após a análise e compreensão das correlações, é proposto um modelo de aprendizado de máquina para prever o comportamento de tratamentos, utilizando conjuntos de dados distintos para treino e avaliação. O contexto é inspirado na competição [Mechanism of Action (MoA) Prediction](https://www.kaggle.com/c/lish-moa) do Kaggle, em parceria com o Laboratory for Innovation Science at Harvard (LISH).

---

## 📁 Estrutura do Projeto

### Anotações de aula (`*.md`)
- **aula1.md** — Python, Pandas e Pharmacia
- **aula2.md** — Estatísticas, dados e distribuições
- **aula3.md** — Correlações e causalidades
- **aula4.md** — Merge e análise de resultados
- **aula5.md** — Machine Learning e Scikit-learn

### Desafios
- **aula1-desafio8.md** — Desafio da Aula 1 (resolvido)

### Notebooks Jupyter
- **Imersao_Dados_Aulas.ipynb** — Desenvolvimento das aulas
- **Desafios.ipynb** — Desenvolvimento dos desafios (também disponível no [Google Colab](https://github.com/henriqueotogami/imersao-dados-3-alura/blob/main/Desafios.ipynb))

### Outros
- **descricao.md** — Descrição do desafio MoA (Kaggle)

---

## 📂 Estrutura do repositório

```
README.md
LICENSE
descricao.md
aula1.md          # anotações: Python, Pandas e Pharmacia
aula2.md          # anotações: estatísticas e distribuições
aula3.md          # anotações: correlações e causalidades
aula4.md          # anotações: merge e análise de resultados
aula5.md          # anotações: Machine Learning e Scikit-learn
aula1-desafio8.md # solução do desafio da aula 1
Imersao_Dados_Aulas.ipynb   # notebook das aulas
Desafios.ipynb              # notebook dos desafios
```

---

## 🛠️ Tecnologias Utilizadas

- **Python 3** — Linguagem de programação
- **Jupyter Notebook** — Ambiente interativo de análise e experimentos
- **Google Colab / Colaboratory** — Execução dos notebooks na nuvem
- **Pandas** — Manipulação e análise de dados (DataFrames, CSV)
- **Scikit-learn** — Modelos e pipelines de Machine Learning
- **Matplotlib** — Visualização de dados e gráficos

---

## 📝 Funcionalidades e Etapas

### Objetivos da imersão (concluídos)
- [x] Aplicar conhecimentos de programação em Data Science
- [x] Descobrir como a Ciência de Dados pode auxiliar na Drug Discovery
- [x] Construir análises de dados e tirar conclusões próprias
- [x] Discutir boas práticas para transmissão clara de informação
- [x] Entender e criar o primeiro modelo de Machine Learning
- [x] Desenvolver um novo projeto para o portfólio

### Desafios por aula
- [x] [Aula 01](aula1-desafio8.md)
- [x] Aula 02
- [ ] Aula 03
- [ ] Aula 04
- [ ] Aula 05

---

## 📚 Cronograma das Aulas

| N° da aula | Data     | Assunto                          |
|:----------:|:--------:|:---------------------------------|
| [Aula 1](aula1.md) | 03/05/21 | Python, Pandas e Pharmacia       |
| [Aula 2](aula2.md) | 04/05/21 | Estatísticas, dados e distribuições |
| [Aula 3](aula3.md) | 05/05/21 | Correlações e causalidades       |
| [Aula 4](aula4.md) | 06/05/21 | Merge e análise de resultados    |
| [Aula 5](aula5.md) | 07/05/21 | Machine Learning e Scikit-learn  |

---

## 🚀 Como Executar

### Opção 1: Google Colab (recomendado)
1. Acesse o notebook [Desafios.ipynb](https://github.com/henriqueotogami/imersao-dados-3-alura/blob/main/Desafios.ipynb).
2. Abra no Colab: **File → Open in Colaboratory** (ou use o link “Open in Colab” se disponível).
3. Execute as células em ordem (Runtime → Run all ou Shift+Enter em cada célula).

### Opção 2: Jupyter local
```bash
# Criar ambiente (opcional)
python -m venv venv
source venv/bin/activate   # Linux/Mac
# ou: venv\Scripts\activate  # Windows

# Instalar dependências
pip install jupyter pandas scikit-learn matplotlib

# Subir o Jupyter
jupyter notebook
```
Em seguida, abra `Imersao_Dados_Aulas.ipynb` ou `Desafios.ipynb` no navegador.

> **Nota:** Os dados (CSV) utilizados na imersão devem ser obtidos conforme indicado no [repositório oficial](https://github.com/alura-cursos/imersaodados3) ou na competição [Kaggle — LISH MoA](https://www.kaggle.com/c/lish-moa).

---

## ⚙️ Como Funciona

### Fluxo do projeto
1. **Carregamento e exploração** — Leitura dos CSVs (tratamentos, resultados por tempo 24h/48h/72h) com Pandas.
2. **Análise exploratória** — Estatísticas descritivas, distribuições e comparação entre drogas e não-drogas.
3. **Correlações e merge** — Análise de correlações entre variáveis e merge de tabelas para um dataset unificado.
4. **Modelo de Machine Learning** — Uso do Scikit-learn para treinar um modelo que prevê o comportamento do tratamento (contexto MoA).
5. **Avaliação** — Análise de métricas e conclusões sobre o modelo e os dados.

### Contexto MoA (Kaggle)
O desafio consiste em prever o **Mecanismo de Ação (MoA)** de compostos a partir de assinaturas celulares (expressão gênica e viabilidade). Os dados vêm de uma tecnologia que mede respostas em ~100 tipos de células; a tarefa é um problema de **classificação multi-rótulo**. Detalhes em [descricao.md](descricao.md) e na [descrição oficial no Kaggle](https://www.kaggle.com/c/lish-moa/overview/description).

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 📖 Referências

- [Imersão Dados — Alura](https://www.alura.com.br/imersao-dados)
- [Repositório oficial — Imersão Dados 3](https://github.com/alura-cursos/imersaodados3)
- [Desafio final — Imersão Dados](https://github.com/alura-cursos/imersao-dados-desafio-final)
- [Competição Kaggle — Mechanism of Action (MoA) Prediction](https://www.kaggle.com/c/lish-moa)
- [Laboratory for Innovation Science at Harvard (LISH)](https://lish.harvard.edu/)
- [Descrição do desafio (este repositório)](descricao.md)

---

## 💡 Motivação

Devido às aulas da faculdade de Engenharia Elétrica, tive dificuldade de acompanhar ao vivo a semana da imersão (embora tenha assistido todas as aulas e codado o que foi mostrado). Este repositório serve para concluir os desafios que não foram finalizados durante o evento e explorá-los com mais calma e criatividade.

---

### Hashtags
`#DataScience` `#ImersaoDados` `#Alura` `#Python` `#Pandas` `#MachineLearning` `#ScikitLearn` `#DrugDiscovery` `#MoA` `#Kaggle` `#Jupyter` `#OpenSource` `#Portfolio`

### Meta Keywords
```
imersão dados, data science, Python, Pandas, machine learning, drug discovery,
MoA, mecanismo de ação, Kaggle, Jupyter, Scikit-learn, análise de dados,
Alura, classificação multi-rótulo, expressão gênica, viabilidade celular
```

---

## 🦁 [Henrique Matheus Alves Pereira](https://github.com/henriqueotogami/)

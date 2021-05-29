# #3 Terceira edicão da [Imersão Dados da Alura](https://www.alura.com.br/imersao-dados)

## [Repositório do projeto oficial (clique aqui)](https://github.com/alura-cursos/imersaodados3)

## [Repositório do desafio final (clique aqui)](https://github.com/alura-cursos/imersao-dados-desafio-final)

![](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/biotechnology.jpg?raw=true)

Photo by <a href="https://unsplash.com/@scienceinhd?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Science in HD</a> on <a href="https://unsplash.com/s/photos/data-science?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

---

### Descricão do projeto:

Analisar uma base de dados armazenada em formato csv, contendo informações de tratamentos fármacos em células, comparando os resultados da utilização de drogas e não-drogas, em três intervalos de tempo distintos (24h, 48h e 72h). 

Após a compreensão da correlação dos dados, é proposto um modelo de aprendizado de máquina para prever o comportamento de determinado tratamento, utilizando outro base de dados para treino do modelo.

---

### Tecnologias utilizadas

- Python 3
- Jupyter Notebook
- Google Colab / Colaboratory
- Pandas
- Sci-kit Learn
- Matplotlib

---

### Etapas:

- [x] Aplicar seus conhecimentos de programação em Data Science
- [x] Descobrir como a Ciência de Dados pode auxiliar na Drug Discovery
- [x] Construir análises de dados e tirar suas próprias conclusões
- [x] Discutir boas práticas para a transmissão transparente e clara de informação
- [x] Entender e criar o seu primeiro modelo de Machine Learning
- [x] Desenvolver um novo projeto para o seu portfólio

---

### Datas:

|N° da aula| Data| Assunto |
:---:|:---:|:----|
| [Aula 1](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/aula1.md) | 03/05/21| Python, Pandas e Pharmacia|
| [Aula 2](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/aula2.md) | 04/05/21| Estatísticas, dados e Distribuições|
| [Aula 3](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/aula3.md) | 05/05/21| Correlações e casualidades|
| [Aula 4](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/aula4.md) | 06/05/21| Merge e análise de resultados|
| [Aula 5](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/aula5.md) | 07/05/21| Machine Learning e Sci-kit Learning|

---

### Desafios concluídos:

- [x] [Aula 01 (clique aqui)](aula1-desafio8.md)
- [ ] Aula 02
- [ ] Aula 03
- [ ] Aula 04
- [ ] Aula 05

---

### Desenvolvimento dos desafios

> [Jupyter Notebook no Google Colab](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/main/Desafios.ipynb)

---

### Fonte / Referência

Esse projeto foi inspirado em um desafio do [Laboratory Innovation Science at Harvard](https://lish.harvard.edu/) disponibilizando os dados em uma competição no [Kaggle](https://www.kaggle.com/c/lish-moa).

---

#### Descrição do desafio no Kaggle

O Mapa de Conectividade, um projeto do Broad Institute of MIT e Harvard, do Laboratory for Innovation Science em Harvard (LISH) e da Biblioteca de Fundos Comuns do NIH de assinaturas celulares integradas em rede (LINCS), apresentam este desafio com o objetivo de avanço no desenvolvimento de medicamentos por meio de melhorias nos algoritmos de previsão do MoA.

Qual é o mecanismo de ação (MoA) de uma droga? E por que isto é importante?

No passado, os cientistas derivavam drogas de produtos naturais ou eram inspirados por remédios tradicionais. Drogas muito comuns, como o paracetamol, conhecido nos Estados Unidos como acetaminofeno, foram colocadas em uso clínico décadas antes que os mecanismos biológicos que impulsionam suas atividades farmacológicas fossem compreendidos. Hoje, com o advento de tecnologias mais poderosas, a descoberta de medicamentos mudou das abordagens inesperadas do passado para um modelo mais direcionado baseado na compreensão do mecanismo biológico subjacente de uma doença. Nessa nova estrutura, os cientistas buscam identificar um alvo proteico associado a uma doença e desenvolver uma molécula que possa modular essa proteína alvo. Para descrever a atividade biológica de uma determinada molécula, os cientistas atribuem um rótulo conhecido como mecanismo de ação ou, abreviadamente, MoA.

Como determinamos os MoAs de um novo medicamento?

Uma abordagem é tratar uma amostra de células humanas com a droga e, em seguida, analisar as respostas celulares com algoritmos que buscam semelhança com padrões conhecidos em grandes bancos de dados genômicos, como bibliotecas de expressão gênica ou padrões de viabilidade celular de drogas com MoAs conhecidos.

Nesta competição, você terá acesso a um conjunto de dados exclusivo que combina a expressão gênica e os dados de viabilidade celular. Os dados são baseados em uma nova tecnologia que mede simultaneamente (nas mesmas amostras) as respostas das células humanas aos medicamentos em um pool de 100 tipos de células diferentes (resolvendo assim o problema de identificação ex-ante, quais tipos de células são mais adequados para um determinado medicamento). Além disso, você terá acesso às anotações do MoA para mais de 5.000 medicamentos neste conjunto de dados.

Como de costume, o conjunto de dados foi dividido em subconjuntos de teste e treinamento. Portanto, sua tarefa é usar o conjunto de dados de treinamento para desenvolver um algoritmo que rotula automaticamente cada caso no conjunto de teste como uma ou mais classes MoA. Observe que, uma vez que os medicamentos podem ter várias anotações MoA, a tarefa é formalmente um problema de classificação com vários rótulos.

Como avaliar a precisão de uma solução?

Com base nas anotações de MoA, a precisão das soluções será avaliada no valor médio da função de perda logarítmica aplicada a cada par de anotação de droga-MoA.

Se for bem-sucedido, você ajudará a desenvolver um algoritmo para prever o MoA de um composto, dada sua assinatura celular, ajudando os cientistas a avançar no processo de descoberta de drogas.

---

### Minhas motivacões

Devido as minhas aulas da faculdade de engenharia elétrica, tive dificuldades de acompanhar as aulas do evento (apesar de ter assistido todas e codei tudo que foi mostrado), e isso pra mim é um bom motivo para finalizar os desafios que eu não pude resolver durante a semana da imersão dados, e resolver com a minha criatividade.

---

## 🦁 [Henrique Matheus Alves Pereira](https://github.com/HenriqueMAP/)

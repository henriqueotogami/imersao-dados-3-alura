## Aula 1 - Desafio 07

### Resumir os aprendizados desta aula

### Desafios desta aula:

- Desafio 01: Investigar o por quê da classe "tratamento" ser tão desbalanceada
- Desafio 02: Plotar as 5 últimas linhas da tabela
- Desafio 03: Proporção das classes de tratamento
- Desafio 04: Quantos tipos de drogas foram investigado
- Desafio 05: Procurar na documentação do Pandas sobre o método `dataframe.query`
- Desafio 06: Renomear as colunas removendo o hífen
- Desafio 07: Melhorar a aparência dos gráficos, utilizando o `matplotlib.pyplot`

---

<!-- <img width="auto" src="https://github.com/HenriqueMAP/HenriqueMap/blob/master/GitHub-Versao2-16-05-21.png?raw=true"> -->

#### Quantidade de tratamentos utilizando drogas VS não utilizando drogas (com_controle)

![Gráfico 1 - Quantidade de tratamentos com droga vs com controle](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/master/aula1-desafio1.-graph1.png?raw=true)

Embora a quantidade de tratamentos utilizando drogas seja igual a 21948, em contrapartida, a quantidade de tratamentos sem drogas (com_controle) é igual a 1866. A princípio, parece ser uma desproporcionalidade, mas isso só fica visível dessa forma porque a análise nesse ponto é rasa, superficial, e precisa ser aprofundada.

#### Quantidade da utilização de cada tipo de substância / composto

> Tabela 1

| Composto | Quantidade |
:---:|:---:|
cacb2b860 | 1866 |
87d714366 | 718 |
9f80f3f77 | 246 |
8b87a7a83 | 203 |
5628cb3ee | 202 |
...| ... |
f5487e91f | 1 |
a9bc2c549 | 1 |
98c94f9b9 | 1 |
18a406358 | 1 |
98a2c9b21 | 1 |

~~~python
Name: composto, Length: 3289, dtype: int64
~~~

Para aprofundar essa análise, é necessário identificar se existem mais de uma substância utilizada no **tratamento sem drogas**. Neste caso, é possível identificar que a substância utilizada foi apenas a denominada `cacb2b860`.

Note que, ao contar quantas vezes ela é utilizada, encontramos o mesmo valor de 1866 utilizado quando verificamos quantos tratamentos foram realizados anteriormente.

Confira abaixo que somente existe essa substância quando filtramos a coluna de "tratamento" para o valor de "com_controle".

#### Verificação de substâncias utilizadas no tratamento "com_controle"

~~~python
array(['cacb2b860'], dtype=object)
~~~

#### Quantidade de utilização das substâncias

> Tabela 2

| tratamento | com_controle	| com_droga |
|   :---:    |      :---:   |   :---:   |
|**composto**|              |           |
|    ---     |       ---    |    ---    |
00199ff52 | 0 | 6
00251fc41 | 0 | 6
00321ea80 | 0 | 12
0034c0847 | 0 | 6
0060e686f | 0 | 6
... | ... |... |
ff9565933 | 0 | 6
ffd66e220 | 0 | 6
ffe357f8f | 0 | 1
ffed8e1c9 | 0 | 6
fff7d208d | 0 | 6

~~~python
3289 rows × 2 columns
~~~

O método `pd.crosstab` do **Pandas** retornou a frequência que cada tipo de substância / droga foi utilizada nos **23814 tratamentos**.

Desse valor, sabemos que precisamos subtrair a quantidade de **tratamentos realizados sem drogas**, que corresponde a 1866 tratamentos.

Assim, **restam 21948**, dos quais podemos verificar com o retorno acima que **são exatamente 3288 drogas utilizadas**, sendo que retiramos apenas 1 do total de linhas que o `pd.crosstab` retorna, **devido a substância do tratamento com controle**.

E se utilizarmos

~~~python
dados['composto'].value_counts() 
~~~

podemos ver que a droga mais utilizada nos tratamentos é a denominada como `87d714366`, da qual é **utilizada 718 vezes**.

Agora sabendo disso, percebemos que a quantidade de tratamentos não utilizando drogas foi maior que qualquer tratamento utilizando uma droga específica.

Ou seja, não existe nenhuma desproporcionalidade.

---

#### Proporção das classes de tratamento

![Gráfico 2 - Proporção de tratamentos com droga vs com controle](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/master/aula1-desafio3-graph2.png?raw=true)

---

#### Melhorar a aparência dos gráficos, utilizando o matplotlib.pyplot

![Gráfico 3 - Quantidade de utilização das 5 primeiras drogas da base de dados](https://github.com/HenriqueMAP/imersao-dados-3-alura/blob/master/aula1-desafio7-graph3.png?raw=true)

---

### 🦁 Henrique Matheus Alves Pereira
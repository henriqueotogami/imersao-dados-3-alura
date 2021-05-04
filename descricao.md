O Mapa de Conectividade, um projeto do Broad Institute of MIT e Harvard, do Laboratory for Innovation Science em Harvard (LISH) e da Biblioteca de Fundos Comuns do NIH de assinaturas celulares integradas em rede (LINCS), apresentam este desafio com o objetivo de avanço no desenvolvimento de medicamentos por meio de melhorias nos algoritmos de previsão do MoA.

Qual é o mecanismo de ação (MoA) de uma droga? E por que isto é importante?

No passado, os cientistas derivavam drogas de produtos naturais ou eram inspirados por remédios tradicionais. Drogas muito comuns, como o paracetamol, conhecido nos Estados Unidos como acetaminofeno, foram colocadas em uso clínico décadas antes que os mecanismos biológicos que impulsionam suas atividades farmacológicas fossem compreendidos. Hoje, com o advento de tecnologias mais poderosas, a descoberta de medicamentos mudou das abordagens inesperadas do passado para um modelo mais direcionado baseado na compreensão do mecanismo biológico subjacente de uma doença. Nessa nova estrutura, os cientistas buscam identificar um alvo proteico associado a uma doença e desenvolver uma molécula que possa modular essa proteína alvo. Como uma abreviação para descrever a atividade biológica de uma determinada molécula, os cientistas atribuem um rótulo conhecido como mecanismo de ação ou MoA.

Como determinamos os MoAs de um novo medicamento?

Uma abordagem é tratar uma amostra de células humanas com a droga e, em seguida, analisar as respostas celulares com algoritmos que buscam semelhança com padrões conhecidos em grandes bancos de dados genômicos, como bibliotecas de expressão gênica ou padrões de viabilidade celular de drogas com MoAs conhecidos.

Nesta competição, você terá acesso a um conjunto de dados exclusivo que combina a expressão gênica e os dados de viabilidade celular. Os dados são baseados em uma nova tecnologia que mede simultaneamente (nas mesmas amostras) as respostas das células humanas aos medicamentos em um pool de 100 tipos de células diferentes (resolvendo assim o problema de identificação ex-ante, quais tipos de células são mais adequados para um determinado medicamento). Além disso, você terá acesso às anotações do MoA para mais de 5.000 medicamentos neste conjunto de dados.

Como de costume, o conjunto de dados foi dividido em subconjuntos de teste e treinamento. Portanto, sua tarefa é usar o conjunto de dados de treinamento para desenvolver um algoritmo que rotula automaticamente cada caso no conjunto de teste como uma ou mais classes MoA. Observe que, uma vez que os medicamentos podem ter várias anotações MoA, a tarefa é formalmente um problema de classificação com vários rótulos.

Como avaliar a precisão de uma solução?

Com base nas anotações do MoA, a precisão das soluções será avaliada no valor médio da função de perda logarítmica aplicada a cada par de anotação do fármaco-MoA.

Se for bem-sucedido, você ajudará a desenvolver um algoritmo para prever o MoA de um composto, dada sua assinatura celular, ajudando os cientistas a avançar no processo de descoberta de drogas.

fonte: https://www.kaggle.com/c/lish-moa/overview/description
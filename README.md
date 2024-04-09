# Learning Agency Lab
 
Importância da Avaliação de Redações: Destaca a importância da escrita de redações como método de avaliação do aprendizado e desempenho dos alunos.

Desafios da Avaliação Manual: Menciona os desafios enfrentados pelos educadores ao avaliarem manualmente as redações dos alunos.

Sistemas de Avaliação de Escrita Automatizada (AWE): Apresenta os AWEs como uma solução para complementar a avaliação manual, fornecendo feedback regular e oportuno aos alunos.

Limitações dos AWEs Tradicionais: Discute como os AWEs tradicionais são limitados devido aos seus custos, o que dificulta o acesso para muitas comunidades.

Necessidade de Soluções de Código Aberto: Destaca a necessidade de soluções de código aberto para avaliação de redações, visando alcançar todas as comunidades com ferramentas educacionais importantes.

Desenvolvimento de Conjuntos de Dados Diversificados: Aborda a importância de conjuntos de dados abrangentes e diversificados para o desenvolvimento de AWEs eficazes.

Objetivo da Competição: Explica o objetivo da competição de desenvolver um algoritmo de pontuação de redação de código aberto que melhore as competições anteriores.

Parcerias e Apoio: Menciona as parcerias entre a Universidade de Vanderbilt, The Learning Agency Lab e o apoio de organizações como a Fundação Bill & Melinda Gates, Schmidt Futures e Iniciativa Chan Zuckerberg.

Disponibilização das Soluções Vencedoras: Destaca que as soluções vencedoras serão lançadas como código aberto para garantir que os resultados da competição estejam amplamente disponíveis.





O conjunto de dados da competição consiste em cerca de 24.000 redações argumentativas escritas por estudantes. Cada redação recebeu uma pontuação em uma escala de 1 a 6 (Link para o Rubrica de Pontuação Holística). Seu objetivo é prever a pontuação que uma redação recebeu com base em seu texto.

Informações sobre Arquivos e Campos
train.csv - Redações e pontuações a serem usadas como dados de treinamento.

essay_id - O ID único da redação
full_text - A resposta completa da redação
score - Pontuação holística da redação em uma escala de 1-6
test.csv - As redações a serem usadas como dados de teste. Contém os mesmos campos que train.csv, exceto pela exclusão da pontuação.

sample_submission.csv - Um arquivo de submissão no formato correto.

essay_id - O ID único da redação
score - A pontuação holística prevista da redação em uma escala de 1-6
Por favor, note que esta é uma Competição de Código.


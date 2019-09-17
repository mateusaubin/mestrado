# mestrado

Fontes em LaTeX para dissertação aprovada no programa de Mestrado _Stricto Sensu_ em Computação Aplicada pela Universidade do Vale do Rio dos Sinos UNISINOS no ano de 2019.

## Resumo / Abstract

Através do modelo He–lastic é proposta uma abordagem de
otimização para o projeto jModelTest que contempla o uso de elasticidade de recursos em um
ambiente de computação em nuvem, resultando em uma arquitetura de elasticidade em duas
camadas, baseada nas tecnologias FaaS e de Orquestração de Contêineres. 

O modelo proposto
foi submetido a uma série de cenários de avaliação que possibilitaram a comparação com o
estado atual do jModelTest e resultaram, considerando tempo de execução e custo ﬁnanceiro,
em um impacto na faixa de 6% a 16%, conforme a quantidade de recursos utilizados. 

Dentre
as contribuições alcançadas por este trabalho merecem destaque o modelo He–lastic, com
sua abordagem baseada em duas camadas de elasticidade que possibilita prevenir custos em
momentos de ociosidade, assim como o estudo de custos detalhando a interação entre as camadas
de elasticidade, e a taxonomia que foi fundamental na classiﬁcação dos trabalhos contemplados
pelo levantamento do estado da arte. 

Futuramente é possível vislumbrar esforços quanto a
otimização da transição entre as camadas de elasticidade, que apresentou sensíveis perdas de
eﬁciência durante a avaliação, assim como melhorias no protótipo e no modelo buscando extrair
maiores ganhos de eﬁciência.


## Repositórios Relacionados

- [jModelTest2](https://github.com/mateusaubin/jmodeltest2): software base utilizado pelo projeto desenvolvido, sendo levemente modificado para emitir _logs_ dos comandos enviados para o [phyml](https://github.com/stephaneguindon/phyml), uma de suas dependências;
- [modeltest-lambda](https://github.com/mateusaubin/modeltest-lambda): protótipo utilizado na avaliação do modelo proposto, responsável por simular a execução do jModelTest em ambientes serverless (AWS Lambda) e de orquestração de containers (AWS Batch) visando um melhor aproveitamento de recursos através da estratégia de execução em duas camadas (de longa e curta duração);
- [modeltest-loadexerciser](https://github.com/mateusaubin/modeltest-loadexerciser): _driver_ para execução dos benchmarks utilizados para estabelecer os resultados tanto do jModelTest2 quanto do protótipo desenvolvido para o modelo He-lastic, disparando a execução e coletando os resultatos dos testes.


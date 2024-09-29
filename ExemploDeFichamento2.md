# Test Automation in Open-Source Android Apps: A Large-Scale Empirical Study

Jun-Wei Lin; Navid Salehnamadi; Sam Malek; (2021) "35th IEEE/ACM International Conference on Automated Software Engineering doi: 9286051

## 1. Fichamento de Conteúdo

O artigo apresenta um estudo empírico abrangente sobre a cultura de automação de testes entre desenvolvedores de aplicativos móveis, analisando mais de 3,5 milhões de repositórios no GitHub e identificando mais de 12.000 aplicativos Android não triviais. O foco da pesquisa foi investigar três aspectos principais: a adoção da automação de testes, os hábitos de trabalho dos desenvolvedores em relação a esses testes e a correlação entre a adoção de automação e a popularidade dos projetos.
Os principais resultados incluem: apenas 8% dos projetos de desenvolvimento de aplicativos móveis utilizam práticas de automação de testes; os desenvolvedores tendem a manter práticas consistentes de automação em diferentes projetos; e projetos populares, medidos pelo número de colaboradores, estrelas e forks no GitHub, são mais propensos a adotar tais práticas. Para aprofundar a compreensão das razões por trás dessas observações, os autores realizaram uma pesquisa com 148 desenvolvedores profissionais, cujas contribuições ajudaram a esclarecer as práticas atuais e as direções futuras para a automação de testes no desenvolvimento de aplicativos móveis.

## 2. Fichamento Bibliográfico
* O estudo investiga a prevalência da automação de testes em aplicativos Android de código aberto, com foco na análise de 12.562 repositórios, considerando apenas aqueles desenvolvidos com o Android Studio. A pesquisa visa entender os desafios e práticas de teste entre desenvolvedores.
Coleta de Dados: Os dados foram coletados de diversos mercados de aplicativos, incluindo a Google Play Store. Uma pesquisa online foi realizada com desenvolvedores dos aplicativos analisados.
* A pesquisa atingiu 7.490 desenvolvedores, resultando em 148 respostas válidas, com uma taxa de resposta de 2,2%
* Apenas 7,98% dos aplicativos analisados continham testes automatizados, um número significativamente menor que estudos anteriores.
* Algumas categorias, como finanças e reprodutores de vídeo, mostraram maior adoção de testes automatizados (19% e 15%, respectivamente), enquanto outras, como compras e namoro, mostraram baixíssima adoção.
* Os principais obstáculos incluem:
Custo e manutenção dos testes.Restrições de tempo.Tamanho ou complexidade do aplicativo.Implicações e Considerações Finais
O estudo revela que a automação de testes em aplicativos Android de código aberto é bastante limitada e que muitos desenvolvedores enfrentam desafios significativos para sua adoção.
Sugestões para futuras pesquisas incluem explorar estratégias para melhorar a adoção de testes automatizados, especialmente em categorias com baixa taxa de testes.

## 3. Fichamento de Citações
* _"Automated testing of mobile apps has received significant attention in recent years from researchers and practitioners alike"_
* _Legacy code not designed to be tested requires lots of refactoring which makes it harder to justify the additional effort to write tests.“… hard to test unexpected GUI aspects or unexpected hardware (manufactor firmware) issues or unexpected permission issues or unexpected Android behavoir or unexpected 3rd party data formats"_
* _"Regarding the developers' compliance with the Test Pyramid practice, Table 10 shows that in more than half of the apps, the ratio of UI tests is higher than 40%, which differs from the recommended ratio of 20%-30% by Google [27]. In other words, the developers put more effort than recommended in writing UI tests."_
* _“I would say they have a direct connection since the quality and rigidness of the app's code can definitely influence an app's popularity.” (direct).

“Projects can only grow to large numbers if they are stable. Automated testing can ensure this happens to some degree.” (direct)_
* _"The fact that there are many local optima in the search space indicates that, for large test suites, the fitness landscapes are likely to be inherently multimodal. This result suggests that global search techniques could outperform local search techniques for regression testing prioritization problems, particularly for larger test suites."_

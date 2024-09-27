# Continuous Integration in Automation Testing

Larrisa Gota; Dan Gota; Liviu Miclea; (2020) "IEEE International Conference on Automation, Quality and Testing, Robotics (AQTR)", doi: https://doi.org/10.1109/AQTR49680.2020.9129990

## 1. Fichamento de Conteúdo

O objetivo geral é implementar uma estrutura de testes automatizados utilizando WebdriverIO e Mocha, com foco na integração contínua.
A metodologia e a pesquisa adotou o padrão Page Object para organizar o código dos testes, garantindo que as ações em elementos não fossem implementadas diretamente nos testes, mas através de métodos que facilitassem a manutenção e legibilidade. Para automatizar a execução dos testes e gerar relatórios, foi realizada a integração com o Jenkins, que permite a compilação e execução remota de projetos. Os testes foram executados em um ambiente de nuvem através do BrowserStack, possibilitando a validação em múltiplos navegadores e sistemas operacionais.
Os resultados demonstraram uma redução significativa no tempo de execução dos testes, com melhorias de até 20% ao utilizar o BrowserStack em comparação com execuções locais. Os relatórios gerados pelo Allure foram detalhados e interativos, permitindo uma análise clara dos resultados dos testes, como a quantidade de testes falhados e a visualização do histórico de builds, o que facilita a tomada de decisões sobre o estado do software em desenvolvimento.

## 2. Fichamento Bibliográfico
* O artigo aborda a crescente importância dos testes automatizados na integração contínua, destacando como eles melhoram a qualidade do software e a eficiência no desenvolvimento.
Ferramentas Utilizadas
* São apresentadas as ferramentas principais: WebdriverIO para automação de testes, Mocha como framework de testes, Jenkins para integração contínua, Allure Reports para relatórios interativos e BrowserStack para execução de testes em diferentes navegadores e sistemas operacionais.
Estrutura de Testes
* A implementação do padrão Page Object é detalhada, que organiza o código de teste, separando a lógica de interação com a interface do usuário da lógica do teste, o que resulta em código mais limpo e reutilizável.
Integração com Jenkins
* A configuração do Jenkins é explicada, incluindo como agendar execuções de testes e gerenciar builds. O artigo enfatiza a importância do Jenkins na execução remota de testes e na coleta de relatórios.
Execução em Nuvem
* O uso do BrowserStack é discutido como uma solução para executar testes em ambientes variados. O BrowserStack permite realizar testes em múltiplos navegadores e plataformas, aumentando a cobertura de testes e eficiência.
Resultados
* O artigo apresenta resultados quantitativos, mostrando a melhoria no tempo de execução dos testes ao usar BrowserStack em comparação a testes locais. Destaca a capacidade de gerar relatórios detalhados que facilitam a identificação de falhas e a análise de desempenho.
Conclusão
* A conclusão ressalta a eficácia da automação de testes em ambientes de integração contínua, promovendo não apenas a velocidade no desenvolvimento, mas também uma melhoria na qualidade geral do software entregue.

## 3. Fichamento de Citações
* _"Running a project with 3 files on a local machine... took 33s. Running the same project... on BrowserStack took 23s."_
* _"The need for automation is always there, but it needs to be done in a 'smart' way."_
* _"Jenkins is the leading open source automation server that provides hundreds of plugins to support building, deploying and automating any project."_
* _"Having a stable grid to run UI tests with Selenium... is really hard."_
* _"This paper aims to implement a solution that combines WebdriverIO JavaScript tests with Mocha Framework to create an automated testing framework."_

# Aprendizagem por Projetos Integrados 2022-1
![logoraculum](https://user-images.githubusercontent.com/54710426/173154765-663752ba-20ba-476f-bdbb-2e141b32df22.PNG)


### Parceiro Acadêmico
UOL: Há anos uma das empresas pioneiras em produtos de tecnologia e informação no Brasil, possuindo diversas frentes que vão de sites de notícias a serviços de hospedagem, entre outros.
Link:  [uol.com.br](http://www.uol.com.br/index.php).



***

### Visão do Projeto
O produto teve como objetivo o monitoramento de uma aplicação, também desenvolvida pelo time, afim de coletar dados e ter a possibilidade de prever e avisar o usuário em caso de falhas iminentes.

![cadastro_rodando](https://user-images.githubusercontent.com/54710426/173150325-e2f3d64a-22f5-4c42-bc92-eb75bb6e155f.gif)
Aplicação de cadastro de usuários desenvolvida em Java e em pleno funcionamento.

![grafana_show](https://user-images.githubusercontent.com/54710426/173150370-decd8e77-da58-436d-8fdc-bd9466be310f.gif)
Gráficos do Grafana exibindo métricas coletadas do sistema via Prometheus.

![analisesurv](https://user-images.githubusercontent.com/54710426/173150997-04031e53-0fa3-48eb-a9e8-31bb2bd8d345.PNG)
Processo de análise de sobrevivência sendo efetuado com base nos dados coletados pelo nosso CSV. (Imagem ilustrativa, para página detalhada clique [aqui](https://github.com/Oraculum-Fatec/api-previsao-de-indisponibilidade-sites/blob/main/SurvivalAnalysis.ipynb)

![Slack_message](https://user-images.githubusercontent.com/54710426/173150382-3d062c22-b85d-4a0d-81aa-19c460708d71.png)
Avisos via canal do Slack alertando queda iminente do sistema até eventual falha.


#### Lista de Requistos 

`Requisitos Funcionais`: 
1. Desenvolver um formulário de cadastro, com os campos: Nome, E-mail, Senha e Celular;
2. Prover uma forma de consulta dos cadastros realizados;
3. Monitorar e coletar dados do uso do cadastro pelos users;
4. Fazer análise de Sobrevivéncia da Aplicação;
5. A partir da análise prever via I.A. falhas iminentes no sistema e alertar os administradores.



`Requisitos não Funcionais`:
1. Desenvolver backend da aplicação formulário utilizando a linguagem java em conjunto do Framework Springboot
2. Tempo de resposta do backend de consulta de cadastros deve ser abaixo de 100ms;
3. Desenvolver o frontend da aplicação formulário utilizando a linguagem JavaScript em conjunto do Framework vue.
4. O tempo de resposta do backend de cadastros deve ser abaixo de 300ms.

***

#### Link do repositório no Github
[Repositório Oracullum](https://github.com/Oraculum-Fatec)


### Tecnologias adotadas na solução

**VueJS:** Utilizado no front-end da aplicação de cadastro;

**Java:** Utilizado para desenvolvimento do backend da aplicação de cadastro;

**Prometheus:** Utilizado para raspagem de dados da aplicação;

**Grafana:** Utilizado para transformas as métricas selecionadas em gráficos e como suporte para consumo de informações da I.A.;

**Python:** Utilizado conforme método recomendado pelo cliente para desenvolvimento da I.A.;

**MySQL:** Banco de dados utilizado para armazenas as informações das aplicações.


### Contribuições Pessoais
Atuei no Backend do projeto, encabeçando o início da pesquisa na primeira Sprint e direcionando o grupo para as soluções que seriam utilizadas, posteriormente atuando no Backend da aplicação de cadastro, configuração e implementação do Prometheus/ Grafana afim de gerar o .csv a ser analisado, seguidos posteriormente pela configuração do Bot via Slack e por fim suporte aos devs da equipe em ajustes críticos da I.A..


### Hard Skills
**Java:** Melhores práticas de programação, desenvolvimento de uma aplicação CRUD Web completa e integração com o MySQL; Sei fazer com suporte;

**Python:** Melhores práticas de programação, suporte no tratamento dos dados a serem consumidos e ajustes nos cálculos da I.A. e análise de sobevivência (Curva Kaplan Meier)

**MySQL:** Administração e envio de dados tratados para o banco, criação de Queries necessárias ao produto, raspagem e tratamento de dados a serem consumidos por I.A.; Sei fazer com suporte;

**Prometheus:** Implementação e coleta de métricas de aplicações diversas, sabendo definir parâmetros necessários para verificação da saúde do sistema e plotando-os via Grafana;


### Soft Skills
Como equipe, consideramos este o projeto mais complexo de todos os oferecidos até hoje, porém mesmo com tal fato, a trajetória do time foi mais tranquila que o esperado devido a constante comunicação e cooperação entre todos os integrantes e também a empresa parceira que foi a todos os momentos solícita com nossas dúvidas ou propostas; 

Sair da zona de conforto de uma aplicação básica para o desenvolvimento de um produto mais completo que demandou mais raciocínio foi algo marcante e definitivamente muito rico para a experiência de todos, alavancando as soft skills que já haviam sendo trabalhadas até então ao longo dos anos com outros clientes, e trazendo à tona a necessidade do uso destas habilidades em seu nível máximo devido ao grau maior de complexidade do projeto e também das demandas feitas pelo cliente.

# Aprendizagem por Projetos Integrados 2021-1
<img src="https://user-images.githubusercontent.com/56441534/142959484-12836894-06f3-4346-91ce-1fb6891da026.png" width="300"/>

A necessidade de uma ferramenta capaz de gerar Atas de Reunião dinâmicas e funcionais levou a empresa parceira a ter a iniciativa de apresentar o tema aos alunos do quarto Semestre de Análise e Desenvolvimento de Sistemas da FATEC São José dos Campos.
As principais funcionalidades da ferramenta deveriam ser:

- Funcionalidades de cadastro;
- Controle de acesso;
- Logs de execução; 
- Geração e monitoramento de ata de reunião; e 
- Assinatura digital.

### Parceiro Acadêmico
IACIT: Empresa brasileira, fundada em 1986 e com capacitação tecnológica para o desenvolvimento de produtos e sistemas aplicados ao Auxílio  e ao Controle do Tráfego Aéreo e Marítimo (CNS/ATM); Meteorologia Radar; Telemetria; Redes Integradas; Comunicação; Defesa e Segurança Pública.
Link:  [iacit.com.br](https://www.iacit.com.br/).


***

### Visão do Projeto
O projeto tem como principal objetivo permitir usuários do nicho corporativo gerirem Atas de reuniões, podendo estas serem geradas de maneira direta e organizada e também monitoradas dentro do sistema, garantindo também a segurança e privacidade dos usuários com diferentes níveis de acesso controlados pelo administrador.


#### Lista de Requistos 

`Requisitos Funcionais` requeridos pelo cliente foram:
1. Cadastro de Usuários, Cadastro de Perfil de Acesso, Cadastro de modelo de ata de Reunião.
    - O cadastro de usuário deve conter os seguintes campos: Nome, Título/Cargo,Área/Empresa, E-mail e Telefone;
    - Todo usuário deve ter pelo menos um perfil de acesso;
    - O perfil de acesso define quais funcionalidades o usuário pode acessar, sendo: 
        - Administrador: Acesso total ao sistema;
        - Usuário: Acesso ao cadastro do modelo de ata de reunião, a geração de ata de reunião, ao monitoramento de ata de reunião e à imprimir ata de reunião em PDF e Excel;
        - Gerência: Acesso aos relatórios do sistema, à aprovação do modelo de ata de reunião e a imprimir ata de reunião em PDF e Excel;
        - A aplicação deve ter pelo menos um usuário administrador o qual não pode ser excluído;

2. Login; Logout;
3. Gerar Ata de Reunião;
4. Monitorar Ata de Reunião;
    - Deve ser exibida uma listagem com a situação es todas as atas de reunião. Esta listagem deve possuir filtros: Por Estado, Por Data de Criação da Ata e Por Pauta;
    - A listagem pode ser ordenada de forma crescente e decrescente;
    - Uma Ata de Reunião pode ter os seguintes estados: Nova, Revisada, Assinada e Enviada.

`Requisitos não Funcionais`:
1. Backend: Linguagem Java (sugestão); 
2. Frontend: HTMLS, CSS 3,15, Angular ou React;
3. Ser usual com dispositivos móveis;
4. Estar disponível no idioma Português do Brasil;
5. Manual de usuário com prints de telas e explicação das funcionalidades;
6. Registros de testes de todas as funcionalidades; e
7. Código fonte do sistema documentado.

***

#### link do repositório no Github
[Repositório](https://github.com/DaviNeves0/EasyATA)


### Tecnologias adotadas na solução

**Java**: Em conjunto do framework `Spring` para criação do sistema web;
**Spring**: Framework java para criação de aplicações web.
**MySQL**: Sistema gerenciador de Banco de Dados Relacional. Utilizado para salvar os cadastros de usuários, seus níveis de acesso e o registro de novas Atas de Reunião, registrando todo o ciclo de vida de uma Ata de Reunião.
**HTML**, **CSS** e **JavaScript**: Criação e desenvolvimento do design da Interface do usuário.
**React**: Uma biblioteca JavaScript para criar interfaces de usuário


### Hard Skills
Dentre as habilidades técnicas, obtive o seguinte avanço:
- Criação de sistema web utilizando linguagem de programação `Java` e conjunto do Framework `Spring`:
    - Sei fazer com ajuda.
- Integração com banco de dados relacional utilizando ORM com `java` e `Hibernate`:
    - Sei fazer com ajuda.

### Soft Skills
Mantendo quase a mesma estrutura do grupo do projeto anterior, tivemos a chance de avançar nosso nível de comunicação e alinhamento de ideias mais ainda do que antes, facilitando o ritmo de trabalho, e, mais uma vez, a equipe fora submetida a um desafio maior e com mais imprevistos durante o trajeto, sendo obrigatória a rápida adaptação a novas situações e flexibilidade em diversos aspectos, tanto interpessoais quanto em relação aos negócios.

 

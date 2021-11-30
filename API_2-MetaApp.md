# Aprendizagem por Projetos Integrados 2020-1
![metalogo](https://user-images.githubusercontent.com/54710426/143992128-c328db19-8d3d-4540-9356-c94ba34203ac.PNG)

O desenvolvimento do projeto foi em torno da necessidade da empresa parceira, de realizar uma gestão de informação mais eficaz para garantir a qualidade, o uso adequado desta informação e gerar valor através dos dados. Tendo em vista a mudança do modelo de operação do Cadastro Positivo.

### Parceiro Acadêmico
SPC - Brasil: Empresa vinculada à CNDL que processa e armazena todas as operações de crédito realizadas por empresas associadas.

Link: [spcbrasil.org.br](https://www.spcbrasil.org.br/).

***

### Visão do Projeto
O tema fora determinado pelo corpo docente A proposta era desenvolver uma solução que permitisse ao usuário efetuar anâlise de dados presentes em arquivos .CSV e a partir disto gerar relatórios com indicadores de qualidade sobre os dados e os negócios com base nas informações de movimentações de crédito. A aplicação visava fornecer as funcionalidades por meio de uma interface gráfica simples e permitir que o relatório gerado fosse salvo no diretório local do usuário; Processo este iniciado apartir de um executável.

![meta_app](https://user-images.githubusercontent.com/54710426/143992026-1d2d6a81-16cf-4d4e-8011-143ae8552221.png)



#### Lista de Requistos 
Os `Requisitos Funcionais` foram aplicados tendo em vista as seguintes Métricas de Qualidade disponibilizadas pela empresa parceira:

1. COMPLETUDE:
    - O campo de cadastro do estado referente a um endereço pode estar preenchido ou não, mesmo sendo obrigatório.

2. CONFORMIDADE:
    - Uma vez preenchido, tal preenchimento pode ser feito seguindo ou não as regras de negócio (formato, tamanho, etc).

3. CONSISTÊNCIA:
    - “Estado” é um dado presente em diversas bases, para um mesmo endereço é importante que todas as bases tenham o mesmo estado cadastrado.

4. UNICIDADE:
    - Em cada base que tenha dados geoespaciais é importante que o mesmo endereço, no mesmo estado, não tenha múltiplos registros.

5. ACURÁCIA:
    - Mesmo preenchido (completude) e no formato adequado (validade), o valor pode não se referir a nenhum estado existente na federação 
(ex: “RG” é uma sigla no formato adequado, porém não simboliza um estado).


Requisitos não Funcionais:
1. Aplicação Desktop.
2. Análise e tratamento de arquivos no formato `xlsx` e `csv`.

***

#### link do repositório no Github
[Repositório](https://github.com/diegosilva789/Projeto_SPC/tree/master)


### Tecnologias adotadas na solução
*HTML e CSS:** Utilizados para desenvolvimento de interface gráfica simples para o usuário;
**Python:** Utilizado para tratamento dos dados contidos em documentos .csv, efetuando a leitura, validação, correção e armazenamento no diretório local do usuário;
**Jupyter notebook:** Utilizado como ferramenta de desenvolvimento colaborativo para o time de devs, facilitando visuzliação e compartilhamento das atualizações do código de forma dinâmica.

### Funcionamento
**Executando o METAapp:**

![68747470733a2f2f692e696d6775722e636f6d2f534b77587a6d772e676966](https://user-images.githubusercontent.com/54710426/143992966-0c4c90c5-8e23-49ea-8156-73b48e029665.gif)

**Visualização do relatório:**

![68747470733a2f2f692e696d6775722e636f6d2f544776376946552e676966](https://user-images.githubusercontent.com/54710426/143992943-496fa056-c437-4778-9e15-a955d29c1372.gif)



### Contribuições Pessoais
Parte do desenvolvimento do backend do projeto, pesquisa conjunta e aplicação da lógica e da biblioteca Pandas e Cx-Freeze para criação do executável do software, tratamento do arquivo CSV contendo os dados, junto com a possibilidade de posteriormente gerar os relatórios.

### Hard Skills

- Análise de dados com python3 de arquivos `xlsx` e `csv`; Sei fazer com autonomia; Primeira experiência com o desenvolvimento efetivo de uma aplicação do início ao fim, utilizando metodologias ágeis e lógica aplicada ao uso de um cliente ao invés de apenas para resolução de problemas simples. Aprendizado especifico daslibraries Pandas e cx-freeze, junto com uso do Jupyter notebook.
**Jupyter Notebook:** Primeiro contato com a ferramenta, que se demonstroufundamental para facilitar o processo de desenvolvimento que estava em mão de diversos desenvolvedores, permitindo fácil compartilhamento e visualizaçáo de informaçóes em tempo real.


### Soft Skills

O projeto foi uma ótima oportunidade para aprender normas para relacionamento com um cliente, e também nos permitiu maior imersão nas metodologias ágeis, mais especificamente o SCRUM.

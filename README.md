# TRABALHO DE PI:  In Nature
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Dayanni Maria :"dadayamaria1@hotmail.com" <dadayamaria1@hotmail.com><br>
Elisa Andrade:elisaaj.es@gmail.com<br>
João Vitor:joao.scheidegger@gmail.com<br>
Nycolly Mendes:nycollydonascimentomendes@gmail.com<br>
...

### 2.MINIMUNDO<br>
Descrever o mini-mundo! (Não deve ser maior do que 30 linhas, se necessário resumir para justar)
Entrevista com o usuário e identificação dos requisitos.(quando for o caso de sistemas com cliente real)
Descrição textual das regras de negócio definidas como um subconjunto do mundo real cujos elementos são propriedades que desejamos incluir, processar, armazenar, gerenciar, atualizar, e que descrevem a proposta/solução a ser desenvolvida.
<br>

O sistema in nature surgiu motivado a incentivar o uso de plantas medicinais para o tratamento de alguns problemas de saúde.Sabemos que nem sempre o uso e medicamentos farmacêuticos é a única solução, e que muitas vezes a solução quenos é oferecida é superfula,uma vez que o uso desses medicamentos podeacabar ocasonado diversos outros problemas.Paraalém da motivação de diminuição do uso de medicamentos que podem afetar a saúdedos usuários, o projeto também tem o objetivo de conservar o que chamamos de "saberes ancestrais",que não estão sendo conservados pela sociedade atual,fazendo com que os conhecimentos sobre tratamentos naturais seja perdido.O sistema é criado com a intenção de facilitar o acesso das pessoas ás informações sobre o uso das plantas. 
> O sistema proposto para o "In Narure" conterá todas as informações que estão na descrição. Das Plantas  serão armazenados o cod_planta  que é o identificador, nome e a imagem. Dos Usuários  serão armazenados nome,senha que é o identificador e o emal. O usuário têm um Tipo de usário, que irá armazenar um id que é identificador e uma descrição.Da Indicação serão armazenados a descrição e o cod_indicacao que será identificador.Da contraindicação serão armazenadas  descrição e o cod_contraind, que é identificador. Dos Efeitos_Adversos serão armazenaado o cod_efeito, que é identificador e a descrição.Do Preparo  serão armazenados um cod_preparo e uma descrição.Do Tipo de preparo serão armazenados um cod_tipo, que é identificador e, uma descrição.
> Um ou vários USUARIOS pode possuir apenas um TIPO_USUARIO, e um TIPO_USUARIO pode possuir  à nenhum ou mais USUARIO.Uma ou várias PLANTAS possuem uma ou mais INDICACAO, e uma ou mais INDICACAO podem ser de uma ou mais PLANTAS. Uma ou várias PLANTAS possuem uma ou várias CONTRAINDICACAO.Nenhuma ou várias PLANTAS contém nenhum ou vários EFEITOS_ADVERSOS, e nenhum ou vários FEITOS_ADVERSOS pode ser de nenhuma ou várias plantas. Uma ou várias PLANTAS possuem um ou mais PREPARO, e um ou vários PREPAROS pode ser de uma ou várias PLANTAS. Um ou mais PREPAROS possui um ou vários TIPO_PREPARO, e um ou vários TIPO_PREPARO pode pertencer à uma ou várias PLANTAS 
 
### 3.PMC<br>
![Exemplo de PMC](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/PMC.jpg?raw=true "PMC")



a) inclusão do PMC desenvolvido pelo grupo <br>

![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/c38963c6-baf0-496d-b2e4-0e23362d8035)


#### 3.1. EAP - Estrutura Analítica do Projeto
a) Incluír imagem da EAP 
b) Dicinário da EAP 

#### 3.2. Requisitos funcionais e não funcionais
Incluir informações de: Identificador , Descrição e Prioridade
Exemplos:<br>
a) <img src="https://raw.githubusercontent.com/discproint/template_projeto_integrador/main/arquivos/requisitos_funcionais.png" width="350" height="100" /> <br>
b) <img src="https://raw.githubusercontent.com/discproint/template_projeto_integrador/main/arquivos/requisitos_nao_funcionais.png" width="350" height="190" /> <br>

#### 3.3 Validação da Ideia.
a) Link do formulário desenvolvido
b) Link para Relatório/Apresentação de resultados obtidos

### 4.Personas e Histórias de usuário<br>
<img ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/8a4ada54-25b8-4d69-94fe-04e430e89450)/> <br>
a) inclusão dos Persons desenvolvidos pelo grupo<br>
<br>
<img ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/d5bae6f1-8649-48cd-8400-e12a30fd4510)
/> <br>
b) inclusão das Histórias de usuário desenvolvidas pelo grupo
<br>


### 5. PROTÓTIPOS DO SISTEMA<br>
Neste ponto a codificação não e necessária, somente as ideias de telas devem ser desenvolvidas. O princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas e/ou descartadas <br>


#### 5.1 PROTÓTIPO DO SISTEMA MOBILE
https://quant-ux.com/#/apps/641afb1405d72326569497d4/design/s13223_79043.html

#### 5.2 PROTÓTIPO DO SISTEMA WEB
https://fenixculatra.github.io/PlantasMedicinais/inNature/index.html

#### 5.3 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
    
> O In Nature possui os  seguintes relatórios:
* Mostre quantos usuários são colaboradora, usuários e administrador
* Mostre quantas plantas tem o msm tipo de contraindicacao
* Mostre quantas plantas tem o msm tipo de indicaçã
* Mostre quantas plantas tem o msm tipo de efeitos adversos
 
 ### 6.MODELO CONCEITUAL<br>
    A) Utilizar a Notação adequada (Preferencialmente utilizar o BR Modelo 3)
    B) O mínimo de entidades do modelo conceitual pare este trabalho será igual a 4.
        * informe quais são as 3 principais entidades do sistema em densenvolvimento
      (se houverem mais de 3 entidades, pense na importância da entidade para o sistema)       
    C) Principais fluxos de informação/entidades do sistema (mínimo 2). <br>Dica: normalmente estes fluxos estão associados as tabelas que conterão maior quantidade de dados 
    D) Qualidade e Clareza
        Garantir que a semântica dos atributos seja clara no esquema (nomes coerentes com os dados).
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas (Aplicar os conceitos de normalização abordados).   
        
![Alt text](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/concept_sample.png?raw=true "Modelo Conceitual")
      
    
#### 7 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (Histórias de Usuário e em qual tela do protótipo aquela HU está sendo realizada).
        b) Protótipo vs Modelo conceitual (Histórias de Usuário e em quais tabelas aquele dado está sendo registrado).
        (modelos devem obrigatoriamente estar em conformidade de rastreabilidade)

### 9	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

### 10	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL

#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.<br>

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 13.1	Integração com Linguagem de programação; <br>
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 
 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 #### 14.2 Apresentação em vídeo <br>

    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")

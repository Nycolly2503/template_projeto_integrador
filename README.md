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
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/8359292a-1254-4e49-b5e7-22838a32ceda)
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/785e4693-9e63-4864-a108-b2bba9446a68)
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/ce2dd3a6-77ab-4ed4-b10f-fa1644a6ad02)

#### 3.2. Requisitos funcionais e não funcionais
Incluir informações de: Identificador , Descrição e Prioridade
Exemplos:<br>
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/493df73a-9f6e-4b19-9d4a-ee9f5ff28296)/> <br>
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/d79bbf58-5080-4a3d-af09-5dfd0a0605d1)/><br>

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
        
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/35cb6c8e-4e05-40ba-8981-4f078b8eb3a5)

      
    
#### 7 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    USUARIO: Tabela que armazena as informações relativas a todos os usuários<br>
    TIPO_USUARIO: Tabela armazena o id e uma descrição sobre cada tipo de usuário, quese divide em cliente,administrador e colaborador.<br>
    PLANTA: tabela que armazena informações sobre plantas<br>
    INDICACAO: Tabela que guarda a indicação de uso de cada planta<br>
    CONTRAINDICACAO: Tabela que guarda todos os tipos de contraindicações <br>
    PREPARO:Tabela que armazena todos os  preparos<br>
    TIPO_PREPARO: Tabela que armazena todod os tipo de preparo<br>
    EFEITOS_ADVERSOS:Tabela que armazena todos os efeitos que as plantas podem causar<br>
    COD_PLANTA: Campo que armazenao código de cada planta<br>
    IMAGEM:Campo que armazena a imagem de cada planta<br>
    COD_CONT: Campo que armazena o código de cada contraindicação<br>
    DESCRICAO: Campo que armazena o passo a passo de um preparo<br>
    DESCRICAO: Campo que armazena a descrição tipo de cada usuário<br>
    DESCRICAO: Campo que armazena a descrição de cada caso de indicação<br>
    DESCRICAO: Campo que armazena a descrição de cada caso de  contraindicação<br>
    DESCRICAO:Campo que armazena a descrição de efeito adverso cada<br>
    COD_PREPARO: Campo que armazena o código de cada preparo<br>
    COD_TIPO:Cmapo que armazena o codigo de cada tipo de preparo<br>
    NOME_TIPO:Campo que guarda o nome de cadatipo de preparo<br>
    CODIGO_EFEITO: campo que armazena o código de cada efeito adverso<br>
    COD_INDICACAO: Campo que armazena o código de cada indicação <br>
    NOME: Campo que armazena o nome de cada usuário<br>
    SENHA: Cmapo que armazena a senha de cada usuário cadastrado<br>
    EMAIL: Campo que armazena o email de cada usuário cadastrado<br>
    ID:Campo que guarda o código de cada tipo de usuário <br>
   
    

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        "Como usuário gostaria de pesquisar sobre as plantas disponíveis no site."
     
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/8da6008e-8656-46e3-85f3-f002cab00c83)/>
        >Tabela PLANTA
     ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/7dfd2782-f1ad-4b7a-aeda-7b624b1c755c)


        >Como usuário gostaria de favoritar as plantas que mais uso para ter acesso rápido dessas plantas
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/40641e6b-6969-4673-804d-5d3a74a74720)
        >Tabela FAVORITA
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/ec6dad83-1cc0-43ae-af52-830dac4b466e)
      


        

        >omo usuário gostaria de ter acesso a todas as plantas para cicatrização
        tela depesquisa
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/1683622a-25cb-45d0-aa0a-71225be5dcbd)
        >Tabela INDICACAO 
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/5dba1876-3555-4723-9d9b-e60d57b61c8b)

        >Como administrador, gostaria que usuários selecionados pudessem fazer partede aquipe.
        Tabela TIPO_USUARIO
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/8af8dd8d-bbef-4c8f-8101-24f38b9b8004)

        >Como usuário gostaria de contribuir inserindo informações que conheço e não estão no sistema 
   ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/de708a71-6451-456a-856d-446f044d0e66)


### 9	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/3cd9f51b-769b-445d-bcba-a6dbaae997c7)




### 10	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        /* in Nature - Lógico: */

CREATE TABLE USUARIO (
    cod_usr serial PRIMARY KEY,
    nome varchar(180),
    email varchar(256),
    senha varchar(20),
    permissao varchar(1)
);

CREATE TABLE PLANTA (
    cod_plt serial PRIMARY KEY,
    nome varchar(80),
    imagem varchar(80)
);

CREATE TABLE PREPARO (
    cod_prp serial PRIMARY KEY,
    descricao varchar(2000)
);

CREATE TABLE INDICACAO (
    cod_inc serial PRIMARY KEY,
    descricao varchar(200)
);

CREATE TABLE CONTRAINDICACAO (
    cod_cinc serial PRIMARY KEY,
    descricao varchar(200)
);

CREATE TABLE EFEITO_COLATERAL (
    cod_eftcol serial PRIMARY KEY,
    descricao varchar(600)
);

CREATE TABLE USUARIO_PLANTA (
    FK_USUARIO_cod_usr serial,
    FK_PLANTA_cod_plt serial
);

CREATE TABLE PLANTA_PREPARO (
    FK_PLANTA_cod_plt serial,
    FK_PREPARO_cod_prp serial
);

CREATE TABLE PREPARO_INDICACAO (
    FK_INDICACAO_cod_inc serial,
    FK_PREPARO_cod_prp serial
);

CREATE TABLE PREPARO_CONTRAINDICACAO (
    FK_CONTRAINDICACAO_cod_cinc serial,
    FK_PREPARO_cod_prp serial
);

CREATE TABLE PREPARO_EFEITO_COLATERAL (
    FK_EFEITO_COLATERAL_cod_eftcol serial,
    FK_PREPARO_cod_prp serial
);
 
ALTER TABLE USUARIO_PLANTA ADD CONSTRAINT FK_USUARIO_PLANTA_1
    FOREIGN KEY (FK_USUARIO_cod_usr)
    REFERENCES USUARIO (cod_usr)
    ON DELETE SET NULL;
 
ALTER TABLE USUARIO_PLANTA ADD CONSTRAINT FK_USUARIO_PLANTA_2
    FOREIGN KEY (FK_PLANTA_cod_plt)
    REFERENCES PLANTA (cod_plt)
    ON DELETE SET NULL;
 
ALTER TABLE PLANTA_PREPARO ADD CONSTRAINT FK_PLANTA_PREPARO_1
    FOREIGN KEY (FK_PLANTA_cod_plt)
    REFERENCES PLANTA (cod_plt)
    ON DELETE SET NULL;
 
ALTER TABLE PLANTA_PREPARO ADD CONSTRAINT FK_PLANTA_PREPARO_2
    FOREIGN KEY (FK_PREPARO_cod_prp)
    REFERENCES PREPARO (cod_prp)
    ON DELETE SET NULL;
 
ALTER TABLE PREPARO_INDICACAO ADD CONSTRAINT FK_PREPARO_INDICACAO_1
    FOREIGN KEY (FK_INDICACAO_cod_inc)
    REFERENCES INDICACAO (cod_inc)
    ON DELETE SET NULL;
 
ALTER TABLE PREPARO_INDICACAO ADD CONSTRAINT FK_PREPARO_INDICACAO_2
    FOREIGN KEY (FK_PREPARO_cod_prp)
    REFERENCES PREPARO (cod_prp)
    ON DELETE SET NULL;
 
ALTER TABLE PREPARO_CONTRAINDICACAO ADD CONSTRAINT FK_PREPARO_CONTRAINDICACAO_1
    FOREIGN KEY (FK_CONTRAINDICACAO_cod_cinc)
    REFERENCES CONTRAINDICACAO (cod_cinc)
    ON DELETE SET NULL;
 
ALTER TABLE PREPARO_CONTRAINDICACAO ADD CONSTRAINT FK_PREPARO_CONTRAINDICACAO_2
    FOREIGN KEY (FK_PREPARO_cod_prp)
    REFERENCES PREPARO (cod_prp)
    ON DELETE SET NULL;
 
ALTER TABLE PREPARO_EFEITO_COLATERAL ADD CONSTRAINT FK_PREPARO_EFEITO_COLATERAL_1
    FOREIGN KEY (FK_EFEITO_COLATERAL_cod_eftcol)
    REFERENCES EFEITO_COLATERAL (cod_eftcol)
    ON DELETE SET NULL;
 
ALTER TABLE PREPARO_EFEITO_COLATERAL ADD CONSTRAINT FK_PREPARO_EFEITO_COLATERAL_2
    FOREIGN KEY (FK_PREPARO_cod_prp)
    REFERENCES PREPARO (cod_prp)
    ON DELETE SET NULL;      
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
       -- Inserts na tabela USUARIO
INSERT INTO USUARIO (nome, email, senha, permissao)
VALUES
    ('João Pedro', 'joaopedro@example.com', 'senha123', 'A'),
    ('Carlos', 'carlos@example.com', 'senha456', 'B'),
    ('Maria Silva', 'mariasilva@example.com', 'senha789', 'A'),
    ('Ana Souza', 'anasouza@example.com', 'senha321', 'B'),
    ('Pedro Henrique', 'pedrohenrique@example.com', 'senha654', 'A');

-- Inserts na tabela PLANTA
INSERT INTO PLANTA (nome, imagem)
VALUES
    ('Capim Limão', 'https://fenixculatra.github.io/PlantasMedicinais/imagens/capim-limao.jpg'),
    ('Camomila', 'https://fenixculatra.github.io/PlantasMedicinais/imagens/camomila.jpg'),
    ('Hortelã', 'https://fenixculatra.github.io/PlantasMedicinais/imagens/hortela.jpg'),
    ('Erva-Cidreira', 'https://fenixculatra.github.io/PlantasMedicinais/imagens/erva-cidreira.jpg'),
    ('Chá Verde', 'https://fenixculatra.github.io/PlantasMedicinais/imagens/cha-verde.jpg');

INSERT INTO USUARIO_PLANTA (FK_USUARIO_id_usr, FK_PLANTA_cod_plt)
VALUES
    (1, 1), -- João Pedro: Capim Limão
    (1, 3), -- João Pedro: Hortelã
    (2, 2), -- Carlos: Camomila
    (2, 4), -- Carlos: Erva-Cidreira
    (3, 1), -- Maria Silva: Capim Limão
    (4, 2), -- Ana Souza: Camomila
    (5, 3); -- Ana Maria: Hortelã

-- Inserts na tabela PREPARO
INSERT INTO PREPARO (descricao)
VALUES
    ('Chá de Capim Limão: Ferver as folhas de capim limão em água por 10 minutos.'),
    ('Chá de Camomila: Colocar as flores de camomila em água quente por 5 minutos.'),
    ('Chá de Hortelã: Adicionar folhas de hortelã em água fervente por 3 minutos.'),
    ('Chá de Erva-Cidreira: Infundir folhas de erva-cidreira em água quente por 7 minutos.'),
    ('Chá Verde: Preparar o chá verde em água quente por 2 minutos.');

-- Inserts na tabela INDICACAO
INSERT INTO INDICACAO (descricao)
VALUES
    ('Alívio de estresse e ansiedade'),
    ('Auxilia na digestão'),
    ('Promove relaxamento e sono tranquilo'),
    ('Ajuda a aliviar dores de cabeça'),
    ('Estimula o metabolismo e auxilia na perda de peso');

-- Inserts na tabela CONTRAINDICACAO
INSERT INTO CONTRAINDICACAO (descricao)
VALUES
    ('Não recomendado para pessoas com alergia a capim limão'),
    ('Pode causar reações alérgicas em pessoas sensíveis à camomila'),
    ('Evitar em casos de refluxo gastroesofágico'),
    ('Não recomendado para pessoas com pressão baixa'),
    ('Em excesso, pode causar insônia e irritabilidade');

-- Inserts na tabela EFEITO_COLATERAL
INSERT INTO EFEITO_COLATERAL (descricao)
VALUES
    ('Nenhum efeito colateral conhecido'),
    ('Possíveis reações alérgicas em algumas pessoas'),
    ('Pode causar irritação estomacal em grandes quantidades'),
    ('Pode causar sonolência em algumas pessoas'),
    ('Em excesso, pode causar nervosismo e palpitações');

-- Inserts na tabela PREPARO_INDICACAO
INSERT INTO PREPARO_INDICACAO (FK_INDICACAO_cod_inc, FK_PREPARO_cod_prp)
VALUES
    (1, 1), -- Chá de Capim Limão: Alívio de estresse e ansiedade
    (2, 2), -- Chá de Camomila: Auxilia na digestão
    (3, 3), -- Chá de Hortelã: Promove relaxamento e sono tranquilo
    (4, 4), -- Chá de Erva-Cidreira: Ajuda a aliviar dores de cabeça
    (5, 5); -- Chá Verde: Estimula o metabolismo e auxilia na perda de peso

-- Inserts na tabela PREPARO_CONTRAINDICACAO
INSERT INTO PREPARO_CONTRAINDICACAO (FK_CONTRAINDICACAO_cod_cinc, FK_PREPARO_cod_prp)
VALUES
    (1, 1), -- Chá de Capim Limão: Não recomendado para pessoas com alergia a capim limão
    (2, 2), -- Chá de Camomila: Pode causar reações alérgicas em pessoas sensíveis à camomila
    (3, 3), -- Chá de Hortelã: Evitar em casos de refluxo gastroesofágico
    (4, 4), -- Chá de Erva-Cidreira: Não recomendado para pessoas com pressão baixa
    (5, 5); -- Chá Verde: Em excesso, pode causar insônia e irritabilidade

-- Inserts na tabela PREPARO_EFEITO_COLATERAL
INSERT INTO PREPARO_EFEITO_COLATERAL (FK_EFEITO_COLATERAL_cod_eftcol, FK_PREPARO_cod_prp)
VALUES
    (1, 1), -- Chá de Capim Limão: Nenhum efeito colateral conhecido
    (2, 2), -- Chá de Camomila: Possíveis reações alérgicas em algumas pessoas
    (3, 3), -- Chá de Hortelã: Pode causar irritação estomacal em grandes quantidades
    (4, 4), -- Chá de Erva-Cidreira: Pode causar sonolência em algumas pessoas
    (5, 5); -- Chá Verde: Em excesso, pode causar nervosismo e palpitações

-- Inserts na tabela PLANTA_PREPARO
INSERT INTO PLANTA_PREPARO (FK_PLANTA_cod_plt, FK_PREPARO_cod_prp)
VALUES
    (1, 1), -- Capim Limão: Chá de Capim Limão
    (2, 2), -- Camomila: Chá de Camomila
    (3, 3), -- Hortelã: Chá de Hortelã
    (4, 4), -- Erva-Cidreira: Chá de Erva-Cidreira
    (5, 5); -- Chá Verde: Chá Verde

-- Inserts na tabela INDICACAO
INSERT INTO INDICACAO (descricao)
VALUES
    ('Promove a saúde cardiovascular'),
    ('Ajuda a aliviar sintomas de gripe e resfriado'),
    ('Contribui para o alívio de dores musculares'),
    ('Auxilia na digestão de alimentos pesados'),
    ('Melhora o sistema imunológico');

-- Inserts na tabela PREPARO_INDICACAO
INSERT INTO PREPARO_INDICACAO (FK_INDICACAO_cod_inc, FK_PREPARO_cod_prp)
VALUES
    (6, 1), -- Chá de Capim Limão: Promove a saúde cardiovascular
    (7, 2), -- Chá de Camomila: Ajuda a aliviar sintomas de gripe e resfriado
    (8, 3), -- Chá de Hortelã: Contribui para o alívio de dores musculares
    (9, 4), -- Chá de Erva-Cidreira: Auxilia na digestão de alimentos pesados
    (10, 5); -- Chá Verde: Melhora o sistema imunológico

-- Inserts na tabela CONTRAINDICACAO
INSERT INTO CONTRAINDICACAO (descricao)
VALUES
    ('Não recomendado para gestantes'),
    ('Evitar em casos de alergia ao ingrediente'),
    ('Não recomendado para pessoas com pressão alta'),
    ('Pode causar irritação gastrointestinal em algumas pessoas'),
    ('Em excesso, pode afetar a absorção de nutrientes');

-- Inserts na tabela PREPARO_CONTRAINDICACAO
INSERT INTO PREPARO_CONTRAINDICACAO (FK_CONTRAINDICACAO_cod_cinc, FK_PREPARO_cod_prp)
VALUES
    (6, 1), -- Chá de Capim Limão: Não recomendado para gestantes
    (7, 2), -- Chá de Camomila: Evitar em casos de alergia ao ingrediente
    (8, 3), -- Chá de Hortelã: Não recomendado para pessoas com pressão alta
    (9, 4), -- Chá de Erva-Cidreira: Pode causar irritação gastrointestinal em algumas pessoas
    (10, 5); -- Chá Verde: Em excesso, pode afetar a absorção de nutrientes

-- Inserts na tabela EFEITO_COLATERAL
INSERT INTO EFEITO_COLATERAL (descricao)
VALUES
    ('Possível irritação na pele'),
    ('Pode causar sonolência em algumas pessoas'),
    ('Podem ocorrer dores de cabeça'),
    ('Pode causar aumento da frequência urinária'),
    ('Pode interferir na qualidade do sono');

-- Inserts na tabela PREPARO_EFEITO_COLATERAL
INSERT INTO PREPARO_EFEITO_COLATERAL (FK_EFEITO_COLATERAL_cod_eftcol, FK_PREPARO_cod_prp)
VALUES
    (6, 1), -- Chá de Capim Limão: Possível irritação na pele
    (7, 2), -- Chá de Camomila: Pode causar sonolência em algumas pessoas
    (8, 3), -- Chá de Hortelã: Podem ocorrer dores de cabeça
    (9, 4), -- Chá de Erva-Cidreira: Pode causar aumento da frequência urinária
    (10, 5); -- Chá Verde: Pode interferir na qualidade do sono

/* 
-- Inserts na tabela USUARIO
INSERT INTO USUARIO (nome, email, senha, permissao)
VALUES
    ('João Pedro', 'joaopedro@example.com', 'senha123', 'A'),
    ('Carlos', 'carlos@example.com', 'senha456', 'A'),
    ('Maria Silva', 'mariasilva@example.com', 'senha789', 'A'),
    ('Ana Souza', 'anasouza@example.com', 'senha321', 'C'),
    ('Ana Maria', 'anamaria@example.com', 'senha321', 'C'),
    ('Sr. Souza', 'anasouza@example.com', 'senha321', 'C'),
    ('Moraes', 'anasouza@example.com', 'senha321', 'C'),
    ('Jacinto', 'anasouza@example.com', 'senha321', 'N'),
    ('Arares', 'arares@gmail.com', 'arai9023ds', 'N'),
    ('Monteiro', 'monteiro83@gmail.com', 'kdjsa92jn3', 'N'),
    ('Joana', 'joana.filha@hotmail.com', 'luies42', 'N'),
    ('Lobato Ferreira', 'l0bato.ferro@gmail.com', 'Laka8932r', 'N'),
    ('João Vitor', 'joao.vitor.sch@hotmail.com', 'BananaFrita32', 'N'),
    ('Nicolas', 'nicolas@gmail.com', 'L0dsani', 'N'),
    ('Nicole', 'nicole73@gmail.com', 'batataB0azona12345543', 'N'),
    ('Maria socorro', 'maria.scorro@hotmail.com', '328ff98293jfs', 'N'),
    ('Karine dos Santos', 'karine.asnto@gmail.com', 'fçome89wr23', 'N'),
    ('Amanda', 'amanda.hasio@gmail.com', 'Laiosed232', 'N'),
    ('Ajudada Silveira', 'ajudada.silva@gmail.com', 'Maionese23', 'N'),
    ('Manita', 'manita097@gmail.com', 'Mariana43', 'N'),
    ('Sucrilhos', 'kassita@hotmail.com', 'KassitinhaMorena32', 'N'),
    ('Matador de porcos', '0matador.de.porcos@gmail.com', 'VouBomar23', 'N'),
    ('Shaolin Almeida', 'shaolin.almeida@gmail.com', 'Jacossa231', 'N'),
    ('Pedro Farange', 'predin45.farange@hotmail.com', 'QueloPlastek213', 'N'),
    ('Orgeio Savant', 'orgeio.savant@hotmail.com', '231093432', 'N'),
    ('Laione', 'laione.13232@gmail.com', 'gaelGareno23', 'N'),
    ('Lionel', 'lionel.messi@gmail.com', 'odiasj90', 'N'),
    ('Messi', 'messi.lionel@hotmail.com', 'Weorkaste4530', 'N'),
    ('Carlos Henrique', 'anasouza@example.com', 'senha321', 'N'),
    ('Pedro Henrique', 'pedrohenrique@example.com', 'senha654', 'A');
*/
#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>

>## Relatório 2
 objetivo quantas indicações cada planta tem

>### RELATÓRIO 3
### objetivo quantas Contraindicações cada planta tem

## Relatório 4
### objetivo quantos efeitos adversos cada planta tem

## Relatório 5
### objetivo quantidade de preparos que cada planta tem

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
    
 #### 13.1	Integração com Linguagem de programação; <br>
 res = pd.read_sql_query("""
 select planta.nome, count(contraindicacao.cod_contraind) as qtd_contraindicacoes from planta inner join
possui_contraindicacao on fk_planta_cod_planta  = planta.cod_planta
inner join contraindicacao on fk_contraindicacao_cod_contraind = contraindicacao.cod_contraind
group by  planta.nome """,conn)

>res = pd.read_sql_query(""" select planta.nome, count(indicacao.cod_indicacao) as qtd_indicacoes from planta inner join
possui_planta on fk_planta_cod_planta  = planta.cod_planta inner join indicacao on fk_indicacao_cod_indicacao = indicacao.cod_indicacao
 group by  planta.nome """,conn)

>res = pd.read_sql_query("""
  select planta.nome, count(contraindicacao.cod_contraind) as qtd_contraindicacoes from planta inner join
 possui_contraindicacao on fk_planta_cod_planta  = planta.cod_planta
 inner join contraindicacao on fk_contraindicacao_cod_contraind = contraindicacao.cod_contraind group by  planta.nome
 """,conn)

>res = pd.read_sql_query("""
select planta.nome, count(efeitos_adversos.codigo_efeito) as qtd_efeitosadversos from planta
inner join contem on fk_planta_cod_planta  = planta.cod_planta
inner join efeitos_adversos on fk_efeitos_adversos_codigo_efeito = efeitos_adversos.codigo_efeito group by  planta.nome
""",conn)

>res = pd.read_sql_query("""
 select planta.nome, count(cod_preparo) as qtd_preparos from planta
 inner join possui_preparo on fk_planta_cod_planta  = planta.cod_planta
 inner join preparo on fk_preparo_cod_preparo = preparo.cod_preparo
  group by  planta.nome """,conn)
>


 
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>



   ## Relatório 1
 >![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/3b8525be-60db-4996-bfaa-adc1329a513d)
>![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/e1409fe4-412d-4daa-8c82-a324239a75f2)

>## Relatório 2
>>![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/bbbaeb5c-998d-4a26-aa13-4b6cf946a175)
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/2485afd3-fec5-4206-bbbf-30365ff0cc29)


>## Relatório 3
>![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/8e71c770-2c6a-48b0-a902-a92ceb6fc94c)

![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/6c48555b-98f5-4fcf-91ca-7a8bdf10d75b)


>## Relatório 4
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/b1358add-af50-4f26-8e30-0e53e8031d38)

![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/c2780f7a-8306-41b4-8604-a00ce0fd3e15)

>## Relatório 5
![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/afd75846-d788-483c-810f-ba18dc25bd84)

 ![image](https://github.com/Nycolly2503/template_projeto_integrador/assets/84751064/f0587487-ce40-4fb4-91d9-445bb6b09bb7)


 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 https://docs.google.com/presentation/d/1xT9hVJdESkGyDGfEE4A-znJO8asSmSBugDWzADf39eg/edit?usp=sharing
 
 #### 14.2 Apresentação em vídeo <br>
https://www.canva.com/design/DAFnVbBeJTI/dfhaHu6VdB4qpC5kQAQIJg/edit?utm_content=DAFnVbBeJTI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

    
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

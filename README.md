## PORTFOLIO ACADÊMICO - PROJETOS INTEGRADORES:

[SEMESTRE-01-2019.2 - *Python-Sqlite3 Web Scrapper - Monitor de Segurança Pública*](https://github.com/ODAGAMMXIX/PFOLIO1_DANZO) 

[SEMESTRE-02-2020.1 - *Java-MySQL Stand Alone App - Gráfico de GANTT para Gestores*](https://github.com/ODAGAMMXIX/PFOLIO2_GANTT)

[SEMESTRE-03-2020.2 - *Java-Oracle - Gamificação, Monetização, Fidelização e Educação Financeira*](https://github.com/ODAGAMMXIX/PFOLIO3_VALCODE)

[SEMESTRE-04-2021.1 - *Java-Oracle API - Recrutamento por Geolocalização et al*](https://github.com/ODAGAMMXIX/PFOLIO4_JOBNATION)

[SEMESTRE-05-2021.2 - *Java-Pentaho-My(SQL)Server-MongoDB-Engajamento Estudantil*](https://github.com/ODAGAMMXIX/PFOLIO5_EDUCALYTICS)

## [SEMESTRE-06-2022.1 - *Python-MongoDB-LGPD Opt-in, Opt-out*](https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT)


# I - RESUMO DO PROJETO (Disciplina: TEMAS AVANCADOS DE BANCOS DE DADOS)

**Desafio:** Desenvolver uma aplicação com banco de dados que resolva uma necessidade da Lei Geral de Proteção de Dados. Foi eleito o "Princípio 5" da LGPD, referente à qualidade  dos  dados:  garantia,  aos  titulares,  de  exatidão,  clareza, relevância  e  **atualização  dos  dados**,  de  acordo  com  a  necessidade  e  para  o cumprimento da finalidade de seu tratamento.

**1) A ARQUITETURA DA APLICAÇÃO**

<details><summary> Arquitetura.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/165441157-5dfd32f0-fa09-41ea-82b9-3c9c73636201.png">
</p>
</details>

**2) CRIA E ATUALIZA CONTRATO (PARA RECEBIMENTO DE COMUNICAÇÕES)**
<details><summary> Contrato.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626339-8e182d75-7d2e-4ac7-8137-514244de1b69.png">
<img src="https://user-images.githubusercontent.com/54047352/166626340-9d461710-2c9c-4c50-b4f4-1d8ad796ace8.png">
</p>
</details>
 
**3) MOSTRA O ÚLTIMO CONTRATO EM VIGOR**
<details><summary> Latest.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626341-69e0d45b-0d3d-4df2-8a24-476e2af35d68.png">
</p>
</details>

**4) CRIA USUÁRIO**
<details><summary>Usuário.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626344-6cce5e90-73b6-4af0-9b0b-875b2b012aec.png">
</p>
</details>

**5) ATRIBUI O CONTRATO AO USUÁRIO (CHAVE: E-MAIL)

<details><summary> "Assinatura".</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626349-8233bd13-d742-4354-96ff-10f96a8c39df.png">
</p>
</details>

**6) RECIBO DO USUÁRIO COM AS ALTERAÇÕES ESCOLHIDAS**
<details><summary> Recibo.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626352-3694be99-fe27-42e5-86a0-0e35cda16967.png">
</p>
</details>

**7) ALTERAÇÃO DE PREFERÊNCIAS COM RECIBO DAS ESCOLHAS**
<details><summary> Altera_Preferências</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626354-daeba86b-2b48-40e1-8d82-b225443f8653.png">
    (usuária: Natasha)
<img src="https://user-images.githubusercontent.com/54047352/166626359-96d2e8f8-feeb-442c-b882-39c8a6fd0ba7.png">
    (usuária: Iron-man)
</p>
</details>

**8) CONSULTA PREFERÊNCIAS DESDE A ÚLTIMA ALTERAÇÃO**

<details><summary> Consulta_Preferências</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626356-d5dd58cb-25e6-4504-b6ef-8f106e929cd5.png">
</p>
</details>


**10) ATRIBUI AS PREFERÊNCIAS A UM DETERMINADO CONTRATO**
<details><summary> Altera_contrato.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626364-67a3aeac-a853-4a34-84c3-4025ded4557d.png">
<img src="https://user-images.githubusercontent.com/54047352/166626366-9936d33d-00a6-4715-b624-09d6c4dfc16d.png">
<img src="https://user-images.githubusercontent.com/54047352/166626368-f17c67a9-377f-4c0f-b8b1-d471d7dee4f2.png">
<img src="https://user-images.githubusercontent.com/54047352/166626369-fd736e7e-24c2-488e-8443-48b5b997ef0e.png">
</p>
</details>


**11) CONSULTA HISTÓRICO DE MODIFICAÇÃO DAS PREFERÊNCIAS**

(Binary JSON contendo um ARRAY de histórico)
<details><summary> Histórico.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/166626370-d6c316a1-ca1d-4899-bbaf-a3f66a63255d.png">
<img src="https://user-images.githubusercontent.com/54047352/166626372-5d75a461-b724-4607-b70a-b2a251e15154.png">
<img src="https://user-images.githubusercontent.com/54047352/166626373-5aed99c0-01bc-41a8-a5b7-f2c4bdbc68e3.png">
<img src="https://user-images.githubusercontent.com/54047352/166626378-17611c2a-ca2f-4bd5-9b1e-7b66aa80471b.png">
<img src="https://user-images.githubusercontent.com/54047352/166626346-142bc1fd-36b1-470c-8f8a-9d6e0e0f8f79.png">
<img src="https://user-images.githubusercontent.com/54047352/166626348-5c13e632-06ac-41ed-9547-57b98f8bf9df.png">
</p>
</details>

CONEXÃO COM *ATLAS*, BD NÃO-ESTRUTURADO EM NUVEM.

<details><summary> (Clique aqui)</summary>
<p align="center">
<img src="https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/aa82d170c540c2ad9a7f03495e7a9bbf81d2b234/imgs/Screenshot%20from%202022-06-19%2023-11-29.png">
</p>
</details>

*asdict*
<details><summary> (Clique aqui)</summary>
<p align="center">
<img src="https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/aa82d170c540c2ad9a7f03495e7a9bbf81d2b234/imgs/Screenshot%20from%202022-06-19%2023-13-24.png">
</p>
</details>

*@staticmethod*
<details><summary> (Clique aqui)</summary>
<p align="center">
<img src="https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/9f9935e8c5b85b2c0366b5e9ba42d5ba8ce6f79a/imgs/Screenshot%20from%202022-06-19%2023-50-10.png">
</p>
</details>

*Recibo* artefato tecnológico com **valor jurídico de prova**
<details><summary> (Clique aqui)</summary>
<p align="center">
<img src="https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/aa82d170c540c2ad9a7f03495e7a9bbf81d2b234/imgs/Screenshot%20from%202022-06-19%2023-14-20.png">
</p>
</details>

Minimalismo do Mongo: apenas 02 colections, sem relacionamento.
<details><summary> (Clique aqui)</summary>
<p align="center">
<img src="https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/aa82d170c540c2ad9a7f03495e7a9bbf81d2b234/imgs/Screenshot%20from%202022-06-19%2023-17-32.png">
</p>
</details>

*Documento* pode conter uma ARRAY de dados, prescindível o relacionamento.
<details><summary> (Clique aqui)</summary>
<p align="center">
<img src="https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/aa82d170c540c2ad9a7f03495e7a9bbf81d2b234/imgs/Screenshot%20from%202022-06-19%2023-18-21.png">
</p>
</details>

# II -  TECNOLOGIAS ADOTADAS NA SOLUÇÃO.

:wrench: ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

:wrench:  Backend: ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 

:wrench:  ![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

:wrench: COMPASS.

:wrench:  IDE: ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white).

:wrench:  ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
:wrench:  ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)

:wrench:  Metodologia *Scrum* e Ágil;

:wrench: OBS Studio / Kdenlive

# III - CONTRIBUIÇÕES INDIVIDUAS/PESSOAIS

:axe: Não se aplica, eis que o projeto foi individual.

# IV - APRENDIZADOS EFETIVOS

**BACKEND.**

:heavy_check_mark: criação de conexão ao **Atlas** (com o Mongo Client), em nuvem, onde o banco não-estruturado está disponível.

:heavy_check_mark: utilização da função *asdict*, que transforma um conjunto de dados num dicionário de dados (mapeamento em memória);

:heavy_check_mark: utilização da classe *staticmethod* para ignorar o primeiro argumento implícito e trata a varredura de todos os *documentos* dentro de uma *Coleção* no ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white).

:heavy_check_mark: Tecnologia com **VALOR JURÍDICO DE PROVA**, o **RECIBO** posterior às alterações provocadas pelo usuário.

**BANCO DE DADO NÃO-ESTRUTURADOS**

:heavy_check_mark: Duas coleções (vis-à-vis tabelas) sem qualquer relacionamento ou substitutivo.
:heavy_check_mark: As alterações são registradas dentro do **documento** *user*, que contém um ARRAY com o histórico de alterações, prescindindo uma entidade específica e relacionamento com as demais.

## Running it up

# USE PYTHON 3.8 IN A V.E.
    virtualenv -p /usr/bin/python3.8 LGPDoptInOptOut

    source LGPDoptInOptOut/bin/activate

#Install dependencies

    pip3 install -r requirements.txt

#Config flask

    export FLASK_ENV=development ; export FLASK_APP=index.py

# flask run

* Running on http://127.0.0.1:5000/

The End.
:arrow_up: 
[`Go Back Up`](#https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT/blob/main/README.md#i---resumo-do-projeto-disciplina-temas-avancados-de-bancos-de-dados).

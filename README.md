Bem Vindo ao Projeto Cidade Iluminada 

# 1  INTRODUÇÃO
O projeto Cidade Iluminada nasceu com a visão de aprimorar o progresso da iluminação pública, trazendo à melhoria da qualidade de vida dos cidadãos, além de fortalecer a conexão dos usuários com os administradores da rede pública. 
  Os usuários têm um papel de grande valia, pois irão enviar  feedbacks do serviço e também especificar pontos na cidade que não têm ou  precisam de iluminação. 
 Já os órgãos terão uma visão exclusiva do mapa da cidade em tempo real, com todos os pontos de iluminação e indicadores de qualidade.
 Além da inclusão no objetivo 11 da agenda 2030 da ODS: Cidades e comunidades sustentáveis. O projeto também se inclina para a percepção  de cidades inteligentes, uma vez que adota um estilo inovador de governança colaborativa. 


## 1.1 MOTIVAÇÃO
 Não é de hoje que a segurança é uma preocupação de todos, quem não se sente inseguro em passar por vias com pouca iluminação? ou pior, sem nenhuma iluminação ?
Pensando nisso, as alunas Josieli Camargo e Rhaísa Soares, alunas no curso de análise e desenvolvimento de sistemas da faculdade Cesusc, criaram o projeto Cidade Iluminada. Este projeto foi idealizado para o aperfeiçoamento das questões de segurança e expansão de cidades inteligentes.
 
| O problema é... | Segurança pública e falta de iluminação. |
| ----------- | ----------- |
| Que afeta... | Um problema que afeta a população em geral. |
| O impacto disto é...| Melhoria na qualidade da iluminação pública, aperfeiçoamento no atendimento e segurança dos cidadãos . |
| A solução seria... | Criar uma plataforma que direcione o(a) órgão público e viabilize  a informação de forma rápida e precisa para o órgão responsável através do mapeamento da cidade. Os usuários têm um papel de grande valia, pois irão enviar feedbacks do serviço e também especificar pontos na cidade que não têm ou precisam de iluminação, através de uma plataforma web e mobile. |
## 1.2 BUSINESS MODEL CANVAS

![modelcanvas](https://github.com/JosieliCamargo/imagens/blob/main/1.png)



## 1.3 VISÃO GERAL DA SOLUÇÃO
 O propósito da aplicação é desenvolver um sistema intuitivo rápido e de fácil acesso , seu código será proprietário. O software será ratificado em duas partes, uma plataforma web para o órgão público se cadastrar e ter acesso às informações, já o usuário comum além da plataforma web terá disponível um aplicativo mobile. 

A perspectiva do usuário comum é ter acesso a uma plataforma de acesso rápido e fácil, onde ele possa obter informações da rede elétrica, solicitar novos pontos de iluminação e também relatar problemas na rede. 

A perspectiva do órgão público é ter acesso a informações tais como qualidade do serviço e pontos de iluminação que estejam com problema ou até mesmo sem luz em tempo real através de um mapa da cidade. 

Este projeto é uma inspiração para melhoria da iluminação pública nas cidades, nota se que há uma demora significativa na solicitação de pontos de iluminação, e também na resolução de problemas voltados a relatos de falta de luz . Pontos que possuem postes estragados ou até mesmo não possuem iluminação. Pensando em viabilizar uma informação rápida e precisa para o órgão responsável através do mapeamento da cidade, pautando todos os pontos com a iluminação. 
É possível  dessa forma também ter acesso a pontos com baixa iluminação através de sensores de luz. 

Pelo número de integrantes ser pequeno inicialmente o ambiente de trabalho será home office com reuniões semanais, podendo conter 2 ou 3 reuniões presenciais para ajustes. 
O preço final do produto irá passar por mais pesquisas para ser definido. 


# 2 DETALHAMENTO DO PROCESSO DE DESENVOLVIMENTO DE SOFTWARE

![Camban](https://github.com/JosieliCamargo/imagens/blob/main/Captura%20de%20Tela%20(34).png)

1.*Especificação de Requisitos*
·Engenharia de Sistema 

·Análise de Requisitos 
 
·Especificação de Sistema

2.*Projeto de Sistema*

·Projeto Arquitetural

·Projeto de Interface

·Projeto Detalhado

3.*Programação (Codificação)*

·Codificação

4.*Verificação e Integração (Verificação)*

·Teste de Unidade e Módulo

·Integração

5.*Manutenção e Evolução*

# 3 ESPECIFICAÇÃO DE REQUISITOS

Esta seção descreve, de forma organizada os itens que caracterizam a finalidade de uso do sistema como, por exemplo, os atores, os requisitos funcionais (RFs), os requisitos não funcionais (RNFs), as regras de negócio (RNs) e o diagrama de casos de uso. O objetivo do documento é fornecer aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação da aplicação.

A prioridade de cada RF e RNF pode ser classificada como “essencial”, “importante” e “desejável”, de acordo com a descrição abaixo:

· Essencial: Um RF ou RNF essencial, se não for atendido, impede que a aplicação entre em funcionamento. RFs ou RNFs essenciais são imprescindíveis, isto é, têm de ser implementados impreterivelmente.

· Importante: Se um RF ou RNF importante não for atendido, a aplicação pode até entrar em funcionamento, mas de forma não satisfatória. RFs ou RNFs importantes deveriam ser implementados, mas, se não forem, não impedirão a implantação e utilização da aplicação.

· Desejável: Um RF ou RNF desejável, por fim, é aquele cuja ausência de implementação não compromete a operacionalização da aplicação, isto é, a aplicação pode funcionar de forma satisfatória mesmo sem sua implementação. Esses RFs ou RNFs podem ser deixados para versões posteriores da solução, caso não haja tempo hábil para implementá-los na versão que está sendo especificada.

## 3.1 ATORES
| Ator | Descrição |
| ----------- | ----------- |
| Órgão público | Prefeituras. |
| Usuário Comum | População em geral. |
| Administrador | Administrador do sistema. |

## 3.2 REQUISITOS FUNCIONAIS
|RF 01: O sistema deve permitir a captura de informação externas obtidas pelo mapeamento feito por drone|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RF 02: O sistema deve permitir que usuários sejam cadastrados, classificando-os como:usuário comum ou órgão público| 
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RF 03: O órgão público poderá avaliar os registros fotográficos, submetidos ao sistema, das atividades realizadas pelos usuários|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RF 04: O sistema permitirá ao órgão público o cadastro, a edição e exclusão de eventos do sistema ( verificar os eventos)|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RF 05: O sistema deve permitir o cadastro do usuário comum solicitando os seguintes campos:
| ---------------- |
NOME COMPLETO:
CPF:
EMAIL:
ENDEREÇO:
DATA NASCIMENTO:|
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RF 06: O sistema deve permitir a submissão de registros fotográficos do evento feitos pelo usuário|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RF 07: O sistema deve permitir o cadastro do órgão público solicitando os seguintes campos:|
| ---------------- |
RAZÃO SOCIAL:
CNPJ:
EMAIL:
ENDEREÇO:|
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|


## 3.3 REQUISITOS NÃO FUNCIONAIS

|RNFT 01: O sistema deve ser desenvolvido utilizando plataforma web para o órgão público e versão mobile para usuário comum|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RNFT 02: O front-end da plataforma web deve ser desenvolvido em CSS, e o back-end em Java Script|
| ---------------- |
|Prioridade: ( x ) Desejável (  ) Essencial ( ) Importante|

|RNFT 03: O sistema deve armazenar os dados em um banco de dados na nuvem (MongoDB atlas)|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RNF04- RNFT 04:  A interface deve ser agradável e de fácil utilização|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|

|RNFT 05: O sistema deve permitir autenticação do sistema com login e senha|
| ---------------- |
|Prioridade: (  ) Desejável ( x ) Essencial ( ) Importante|

|RNFT 06: O sistema deve  permitir a redefinição de senha através do email cadastrado|
| ---------------- |
|Prioridade: (  ) Desejável ( x ) Essencial ( ) Importante|

|RNFT 07: A localização será extraida através da foto enviada na solicitação, utilizando a geolocalização fornecida pela mesma|
| ---------------- |
|Prioridade: (  ) Desejável ( x ) Essencial ( ) Importante|



## 3.4 REGRAS DE NEGÓCIO

|RN01- O software somente será entregue ao órgão público que realizar o pagamento|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|


|RN02- As informações serão atualizadas semanalmente para o órgão público|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|


|RN05- O software estará de acordo com as leis LGPD e as leis vigentes do seu ramo|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|


|RN06- Tratamento dos dados.|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|


|RN07- Segurança de dados.|
| ---------------- |
|Prioridade: ( ) Desejável ( x ) Essencial ( ) Importante|



# 4 DIAGRAMAS DE CASOS DE USO
![alt text](https://github.com/JosieliCamargo/imagens/blob/main/use-case.png)

# 5 REFERÊNCIAS
 https://www.markdownguide.org/cheat-sheet/
 https://icmcjunior.com.br/desenvolvimento-de-software/?gclid=Cj0KCQiA1NebBhDDARIsAANiDD0eufcjWG7SBogi0KMd4SzErzShQ4OMrSNF8PpKQ9TR6swdmnFNlwIaAv1tEALw_wcB
 https://classroom.google.com/c/NDg4NzAyMjA4NzY2/m/NDkwNDk5OTA3OTUw/details
 https://classroom.google.com/c/NDg4NzAyMjA4NzY2/m/NTUyMjg3OTkwMDgw/details
 https://classroom.google.com/c/NDg4NzAyMjA4NzY2/a/NTQ5NTI2MDMwMTgy/details
 https://classroom.google.com/c/NDg2ODQ4NTc0MTEw/m/MzYzNDM2MjE0MjY0/details

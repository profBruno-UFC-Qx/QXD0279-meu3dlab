# :checkered_flag: Meu 3d Lab

É um marketplace onde pessoas que tem impressoras 3d podem oferecer o uso de suas impressoras
e outas pessoas podem contratar somente o uso para imprimir algum projeto 3d delas. Basicamente
é o timesharing de impressora 3d

## :technologist: Membros da equipe

Lucas Almeida Barbosa - 495 000 - Sistemas de Informação

## :bulb: Objetivo Geral

O principal objetivo é otimizar a utilização de impressoras 3d e diminuir
o custo de uso para pessoas que precisam de algo pontual

## :eyes: Público-Alvo

Pessoas que querem usar impressoras 3d para projetos simples, mas não tem impressora e
pessoas que tem uma impressora 3d que está sendo subutilizada podem ganhar algum dinheiro
com elas

## :star2: Impacto Esperado

O principal impacto é conseguir facilitar o primeiro acesso a utilização de impressoras 3d sem o investimento inicial alto em uma impressora

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

O projeto tem 3 tipos de usuários: admin, usuário comum e o usuário não logado

O usuário não logado consegue ver a landing page para a propaganda do site e acessar a listagem
de impressoras que podem ser utilizadas, mas ele precisa fazer a conta para conseguir contratar algum negócio

O usuário comum pode ter uma ou mais impressoras às quais ele aluga o uso
O usuário comum pode também encomendar a impressão para outro usuário que postou o serviço da sua impressora

O usuário admin tem todas as capacidades dos usuários comuns
O usuário admin consegue acessar os dados de todos os usários do site

> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post: Principais funcionalidades da aplicação

### Usuário não logado

- Listagem de impressoras para uso
- Acesso a home da aplicação

### Usuário logado

- Todos os acessos acima
- Possibilidade de contratar o uso de uma impressora
- Ver as impressoras que ele tem listadas para terceirização
- Adicionar impressora para terceirizar
- Deletar impressora para terceirizar
- Ver demandas que foram atribuidas a cada uma das suas impressoras
- Ver status da sua impressão

### Usuário admin

- Todos os acessos dos usuários acima
- Dashboard de informações sobre usuários e impressões gerais do app

## :spiral_calendar: Entidades ou tabelas do sistema

- Usuário comum
- Usuário admin
- Impressoras
- Impressões

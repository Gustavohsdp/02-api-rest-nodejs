# Requisitos funcionais

  - [x] O usuário deve poder criar uma nova transação;
  - [x] O usuário deve poder obter um resumo da sua conta;
  - [x] O usuário deve poder listar todas as transações que já ocorreram;
  - [x] O usuário deve poder visualizar uma transação unica;

# Regras de negocios

  - [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
  - [x] Deve ser possível identificarmos o usuário entre as requisições
  - [x] O usuário só pode visualizar transações o qual ele criou;


# Requisitos não funcionais

# Teste unitarios
  - Unidade da sua aplicação

# Teste de integração
  - comunicação entre duas ou mais unidades

# E2E -> ponta a ponta
  - Simula um usuário operando a aplicação
  - Exemplo front-end
    - Abre a página de login, digite o texto gustavohsdp@gmail.com no campo com id email, clique no botão x
  - Exemplo back-end
    - chamadas HTTP, WebSockets

# Pirâmide de testes
  -E2E (não dependem de nenhuma tecnologia, arquitetura) - são testes lentos

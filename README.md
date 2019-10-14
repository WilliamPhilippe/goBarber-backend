# goBarber
O GoBarbar é um serviço de gerenciamento de salões de beleza e barbearias. Há dois tipos de usuário, o cliente e o cabeleireiro/barbeiro. O barbeiro pode se cadastrar no aplicativo, com uso de e-mail e senha. Pode disponibilizar horários disponíveis, etc. O cliente pode agendar um horário, consultar horários marcados, cancelar agendamentos, etc.

### Plataformas
Neste repositório se encontra o backend do GoBarber, desenvolvido em NodeJS.
A versão web pode ser encontrada aqui, e a versão mobile pode ser encontrada aqui. Em ReactJS e React Native

### Desenvolvimento do backend
O backend tem a estrutura de uma API Rest desenvolvida totalmente em NodeJS.
Os bancos de dados usados foram o Postgres, para armazenamento comuns de dados. O MongoDB para armazenamento das notificações de eventos, que serão enviadas ao front-end. O Redis para uma fila de envio de e-mails.

Para cada um dos bancos de dados foram usados containers do Docker, para isolamento dos sistemas.

A lib JWT (javascript web token) foi usada para autenticação de sessões.

O Sentry foi usada para testes e log de erros em desenvolvimento e produção.

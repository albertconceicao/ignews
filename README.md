# ignews
Projeto desenvolvido em Next.js para representar um blog, utilizando Prismic CMS para gerar os posts e por meio da API alimentar a aplicação e o FaunaDB para poder armazenar as inscrições e realizar a disponibilização do conteúdo inteiro dos posts caso o usuário esteja inscrito e com a sua assinatura ativa. O gerenciamento de assinaturas e checkout foi feito com o Stripe. O motivo de utilizar o Next.js é por conta que o blog conta com páginas estáticas que precisam ser atualizados em um determinado período, além do SSR e do melhor comportamento com os motores de busca do Google.

Para poder acessar e rodar o projeto na sua máquina, basta entrar na pasta e rodar o comando yarn dev

# nlwHeat_back
Este projeto foi criado com Node.JS para ser o backEnd da aplicação do NLW Heat
Projeto produzido durante a Next Level Week Heat (NLW Heat) da Rocketseat

Este projeto exercita o uso de banco de dados usando Prisma e também o conceito de real-time com o Socket.io, além de fazer autenticação usando o GitHub

Tecnologias
Prisma, Typescript, Socket.io, Node.js, Yarn

Ferramentas utilizadas
https://efficient-sloth-d85.notion.site/Instala-o-das-ferramentas-91964f6757894d6db05fc09ce97ee5b9

Executando o projeto
Crie uma conta no GitHub, após isso siga as instruções a seguir:

1 - Crie uma nova aplicação em seu GitHub: Settings > Developer Settings ou Clique Aqui!
2 - Guarde seu client_Id e client_secret em algum local de segurança
Configurações do Projeto
Configure o arquivo .env da aplicação conforme o .env.example

GITHUB_CLIENT_ID= 
GITHUB_CLIENT_SECRET= 
JWT_SECRET=VALORALEATORIO 
Caso queira visualizar seu banco de dados:

yarn prisma studio //Caso queira visualizar seu banco de dados
Adicione um valor que servirá de chave para o JWT_TOKEN, você pode utilizar o MD5 Generator.

Após isso, rode os seguintes comandos:

yarn
yarn prisma migrate dev //Irá criar o banco de dados
yarn dev //Irá executar o projeto
(Verifique as permissões de escrita/leitura caso apresente algum erro)

O projeto estará escutando a porta 4000 (http://localhost:4000)

POSTMAN COLLECTION (Opcional)
Acesse seu Postman, clique em "Collections" após isso em "Import" > Link

e cole este link para importar: https://www.getpostman.com/collections/515846416c1a811546da

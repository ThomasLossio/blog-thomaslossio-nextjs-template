# Índice
- [Sobre](#-sobre)
- [Tecnologias](#-tecnologias)
- [Executando o projeto](#-executando-o-projeto)

## 📋 Sobre

Este projeto, **blog-thomaslossio-nextjs-template**, foi baseado no [template de blog do NextJS](https://github.com/vercel/next.js/tree/canary/examples/blog-starter-typescript) e incrementado com a [API Routes](https://nextjs.org/docs/api-routes/introduction) junto com o acesso ao MongoDB para contagem de visitas dos posts conforme o [tutorial da RocketSeat](https://blog.rocketseat.com.br/criando-um-blog-com-contador-de-visitas-usando-nextjs-e-mongodb/). 

Projeto foi realizado como início dos meus estudos com o NextJS. 😁

---

## 🚀 Tecnologias

O projeto utiliza-se das seguintes tecnologias:

- [NextJS](https://nextjs.org/);
- [Yarn](https://yarnpkg.com/);
- [TypeScript](https://github.com/microsoft/TypeScript);
- [API Routes](https://nextjs.org/docs/api-routes/introduction);
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas);

---

## 👨‍💻 Executando o projeto

Após realizar o clone do repositório, através do terminal, use o comando a seguir para instalar as dependências do projeto:

```sh
yarn
```

Aguarde um pouco para que o projeto tenha suas dependências instaladas.

Quando as dependências finalizarem, crie um arquivo na raiz do projeto com o nome `.env.local` e adicione as seguintes variáveis de ambiente:

```
MONGODB_URI=
MONGODB_DB=
```

Conforme informado na seção de [Tecnologias](#-tecnologias), foi usado o MongoDB Atlas, onde é possível criar um cluster gratuito (com pouco espaço de armazenamento) para realizar os testes com o MongoDB.

Caso você esteja usando alguma instância do MongoDB localmente, basta pegar a url de acesso e definí-la em `MONGODB_URI`, além de você criar o banco de dados e definir em `MONGODB_DB`.

Após a configuração, utilize o seguinte comando:

```sh
yarn dev
```

Agora basta acessar no navegador e testar!

---
Desenvolvido 🙃 por Thomas Lossio.
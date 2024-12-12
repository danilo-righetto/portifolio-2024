# Danilo Righetto's website 2024

Criando um novo site, utilizando [nextjs](https://nextjs.org/), [tailwind](https://tailwindui.com/documentation) e [Hygraph CMS](https://hygraph.com/), contendo os principais projetos e competências para apresentar aos novos clientes e futuros recrutadores.

## Iniciando o projeto com Docker

**Atenção**: verifique se o **Docker** e o **Docker Compose** estão instalado no seu ambiente antes de executar os comando á seguir!

Antes de subir o projeto com todos os serviços necessários para o seu correto funcionamento, execute o comando para construir as imagens:

```bash
docker-compose build --no-cache
```

Em seguida, execute o comando abaixo para subir todos os serviços necessários:

```bash
docker-compose up -d
```

Após isso acesse [http://localhost:3000](http://localhost:3000).

## Instalação sem o Docker

Para iniciar o projeto execute os comando abaixo: 

```bash
  npm install #para instalar as dependencias do projeto
  npm run dev #para subir o projeto na porta 3000
```

Após a execução dos dois comando acesse [http://localhost:3000](http://localhost:3000).

## Stack utilizada

- **[Nextjs](https://nextjs.org/)** - (Versão 15.0.3 - Turbopack)
- **[Tailwind](https://tailwindui.com/documentation)**
- **[PNPM](https://pnpm.io/pt/)**
- **[Lucide](https://lucide.dev/)** - (Biblioteca de Icones)
- **[Hygraph CMS](https://hygraph.com/)** - CMS contendo as informações que a aplicação vai consumir (projetos e informações pessoais)

## Autores

- [Github - @danilo-righetto](https://github.com/danilo-righetto)
- [Linkedin - @danilo-righetto](https://www.linkedin.com/in/danilo-righetto/)

## Fonte

- [Criando Portfólio com Next.js 13 - #01](https://youtu.be/DKS_KAmPwvs?si=dXGTAl4o3chLtS5y).
- [Criando Portfólio com Next.js 13 - #02](https://www.youtube.com/watch?v=89hYBEXKpqs&t=9s).
- [Criando Portfólio com Next.js 13 - #03](https://www.youtube.com/watch?v=juJzTio04WQ).

## Licença

Esta aplicação é um software de código aberto licenciado pelo [MIT license](https://opensource.org/licenses/MIT).
# DSMovie
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/henriquebenjamim/dsmovie/blob/main/LICENSE) 

# Sobre o projeto

https://henriquebenjamim-dsmovie.netlify.app/

DSMovie é uma aplicação full stack construída durante a 6ª edição da **Semana DevSuperior** (#sds6), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um catálogo de filmes que podem ser avaliados utilizando apenas um campo de email e o da pontuação. O catálogo é fornecido por um banco de dados relacional com o auxílio de um serviço em nuvem. 


## Layout web
![Web 1](https://github.com/henriquebenjamim/assets/blob/main/sds6/web1.PNG)

![Web 2](https://github.com/henriquebenjamim/assets/blob/main/sds6/web2.PNG)

## Modelo conceitual
![Modelo Conceitual]() No momento sem MC

# Tecnologias utilizadas
## Back end
- Java
- Spring
- Postman (Nos momentos de banco de dados local)
## Front end
- HTML / CSS / JS / TypeScript
- React
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto
 Pela internet - sem instalações: acessar esse site e aguardar um pouco (isso se dá pois o serviço gratuito do heroku desliga a atividade depois de 30 minutos de inatividade).
 https://henriquebenjamim-dsmovie.netlify.app/
 
 Pelo seu computador:
## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://https://github.com/henriquebenjamim/dsmovie

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://https://github.com/henriquebenjamim/dsmovie

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Henrique Benjamim

[Veja o perfil do Henrique no Linkedin](https://www.linkedin.com/in/henriquebenjamim "Clique aqui")

[Atalho para voltar ao perfil do Github](https://github.com/henriquebenjamim "Clique aqui")

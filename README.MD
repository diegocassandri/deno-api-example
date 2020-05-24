# Deno REST API

Uma API REST simples construida com DENO e Oak.Faz parte do artigo publicado no meu blog: 

> [Construindo uma API Rest com Deno](https://www.diegocassandri.com/2020-05-24-Desenvolvendo-uma-API-Rest-com-Deno/)

## Para rodar o projeto

deno run --allow-net server.ts

Routes

|GET| /api/v1/products|
|GET|      /api/v1/products/:id|
|POST|     /api/v1/products|
|PUT|      /api/v1/products/:id|
|DELETE|   /api/v1/products/:id|
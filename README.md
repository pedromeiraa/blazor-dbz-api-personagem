<<<<<<< HEAD
# BlazorViaCep

Aplicação desenvolvida em Blazor WebAssembly para consultar informações de personagens da franquia Dragon Ball usando a API pública oficial.

## Funcionalidades

- Busca de personagem por ID
- Exibição do nome e planeta de origem
- Listagem das transformações e KI de cada personagem
- Tratamento de erros para falhas de conexão ou personagem inexistente

## Tecnologias

- .NET 10
- ASP.NET Core
- Blazor WebAssembly
- HttpClient

## Estrutura da aplicação

A página principal da consulta está em:

- `BlazorViaCep/Pages/Personagem.razor`

Ela acessa o endpoint:

- `https://dragonball-api.com/api/characters/{id}`

## Requisitos

- .NET SDK 10.0
- Navegador moderno

## Como executar

No diretório do projeto, execute:

```bash
dotnet restore
dotnet run
```

Ou, se preferir rodar diretamente a partir da pasta do projeto:

```bash
cd BlazorViaCep
dotnet restore
dotnet run
```

Após iniciar, abra a URL exibida no terminal (normalmente `http://localhost:5000` ou outra porta atribuída pelo ASP.NET).

## Observação

A aplicação foi criada como exemplo de consumo de API em Blazor, com foco em uma interface simples para consulta de personagens por ID.
=======
# blazor-dbz-api-personagem
>>>>>>> 0f144b9f8dbc238086e6226b59ae712a18251cbc

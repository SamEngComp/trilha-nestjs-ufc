# Trilha NestJS na Prática

Material de apoio da **Trilha NestJS na Prática** — uma sequência de aulas construindo, do zero, uma API REST completa com NestJS: arquitetura, validação de dados, banco de dados com Prisma, autenticação com JWT e recursos avançados como Swagger e Docker.

Cada aula parte de onde a anterior parou: o mesmo projeto (`nest-api-curso`) vai crescendo aula a aula, sempre com uma explicação conceitual seguida de código ao vivo.

Material produzido para a disciplina **CK0207 — Desenvolvimento de Software para Web**, da Universidade Federal do Ceará (UFC), sob orientação do **Prof. Dr. Fernando Antônio Mota Trinta**.

Assista à trilha completa no YouTube: [https://www.youtube.com/playlist?list=PLVQILFQ444eo](https://www.youtube.com/playlist?list=PLVQILFQ444eo)

---

## O que tem neste repositório

Para cada aula, dois tipos de material:

| Material | Formato | Descrição |
|---|---|---|
| **Slides** | `.pdf` | Os slides usados na gravação da aula |
| **Apostila** | `.pdf` | Material de leitura da aula — conceito + laboratório passo a passo, tudo em um só documento |

## Estrutura do repositório

```
.
├── aulas/
│   ├── aula-1/
│   │   ├── aula-1.pdf
│   │   └── aula-1-apostila.pdf
│   ├── aula-2/
│   │   └── ...
│   ├── aula-3/
│   ├── aula-4/
│   ├── aula-5/
│   ├── aula-6/
│   ├── aula-7/
│   ├── aula-8/
│   └── aula-9/
└── README.md
```

## Trilha de aulas

| Aula | Tema | Conteúdo |
|---|---|---|
| 1 | Introdução ao Framework e Arquitetura | Motivação, limitações do Express, arquitetura do Nest, Controllers/Services/Modules, Injeção de Dependências, Nest CLI |
| 2 | Laboratório: Primeira API REST | Criação de Controllers, Services e endpoints REST |
| 3 | DTOs e Validação de Dados | DTOs, decorators, ValidationPipe, class-validator, class-transformer |
| 4 | Laboratório: CRUD Completo | Update, Delete, tratamento de erros, boas práticas REST |
| 5 | Integração com Banco de Dados | Conceitos de ORM, Prisma, modelagem de entidades, migrations, SQLite/PostgreSQL |
| 6 | Laboratório: Persistência de Dados | Conectando o Prisma ao NestJS (PrismaService), operações de persistência (create, update, delete), consultas ao banco (findMany, findUnique) |
| 7 | Autenticação com JWT | Autenticação vs. Autorização, JWT, Passport, Guards, hash de senhas com bcrypt |
| 8 | *(em produção)* | Laboratório: Proteção de Rotas |
| 9 | *(em produção)* | Recursos Avançados (Swagger, Interceptors, Docker) |

> **Nota sobre a numeração:** as Aulas 7, 8 e 9 correspondem às Aulas 9, 10 e 11 da ementa oficial da disciplina (Autenticação com JWT, Proteção de Rotas e Recursos Avançados). A numeração foi ajustada nesta trilha para manter a sequência de vídeos sem lacunas.

## Tecnologias usadas no projeto do curso

- [NestJS](https://nestjs.com/)
- TypeScript
- [Prisma ORM](https://www.prisma.io/) (SQLite em desenvolvimento)
- class-validator / class-transformer
- Passport / JWT / bcrypt

## Como acompanhar

1. Assista ao vídeo da aula (slides + explicação).
2. Abra a apostila em PDF correspondente — ela tem o mesmo conteúdo, em formato de leitura, mais o passo a passo de código completo.
3. Siga o laboratório da apostila no seu próprio projeto, criado a partir da Aula 2 (`nest-api-curso`).

Cada aula assume que o projeto das aulas anteriores já existe — não é necessário recriar o projeto do zero a cada aula.

## Autor

Material organizado e produzido por **Samuel Sales Furtado**, a pedido do Prof. Dr. Fernando Antônio Mota Trinta, para a disciplina CK0207 (UFC).

## Uso

Este material foi produzido para fins educacionais, como apoio à disciplina CK0207 da UFC. Sinta-se à vontade para usar como referência de estudo.

# Guia GitHub do ARGOS

## Sobre o agente

O Guia GitHub do ARGOS é um agente de inteligência artificial criado para orientar os integrantes da equipe na utilização e organização dos repositórios do projeto.

O agente fornece instruções passo a passo e considera as regras de colaboração definidas pela equipe.

## Acesso

[Conversar com o Guia GitHub do ARGOS](COLE_AQUI_O_LINK_DO_AGENTE)

## O que o agente pode fazer

- Informar em qual repositório e pasta cada arquivo deve ser colocado.
- Orientar a criação de branches e commits.
- Ensinar como realizar push e abrir Pull Requests.
- Orientar o processo de revisão, aprovação e merge.
- Ajudar na organização da documentação técnica e de UX.
- Explicar como relacionar alterações às demandas do Jira.
- Adaptar as instruções para IntelliJ IDEA, VS Code, GitHub Desktop, terminal ou site do GitHub.

## Repositórios considerados

- `.github`: perfil e configurações compartilhadas.
- `argos-docs`: documentação, UX, planejamento e artefatos.
- `argos-web-crud`: aplicação Java/Maven com Model, DAO, Servlet, JDBC e PostgreSQL.
- `argos-bd`: modelagem e scripts do banco de dados.
- `argos-landingpage`: landing page em HTML, CSS e JavaScript.
- `argos-ai`: documentação, prompts e aplicações de inteligência artificial.

## Regras principais

- Não realizar alterações diretamente na branch `main`.
- Trabalhar em uma branch própria para cada atividade.
- Abrir um Pull Request para integrar alterações.
- Solicitar a revisão de outro integrante.
- Utilizar **Squash and merge** após a aprovação.
- Nunca incluir senhas, tokens ou credenciais nos repositórios.
- Utilizar somente chaves reais do Jira.
- Considerar apenas os requisitos do primeiro ano nesta etapa do projeto.

## Arquivos relacionados

- [Prompt do sistema](./prompt-sistema-github-argos.md)
- [Base de conhecimento](./base-de-conhecimento.md)

## Observação

O agente fornece orientações, mas não realiza alterações diretamente nos repositórios. O integrante continua responsável por conferir os arquivos, testes e informações antes de cada commit ou Pull Request.

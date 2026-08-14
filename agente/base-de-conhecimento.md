# Base de conhecimento do Guia GitHub do ARGOS

## Objetivo

Registrar os documentos utilizados pelo agente para responder perguntas sobre a organização, os repositórios e o fluxo de colaboração do ARGOS.

## Documentos utilizados

| Documento no agente | Origem | Finalidade |
|---|---|---|
| `requisitos-argos-primeiro-ano.pdf` | Documento fornecido pela equipe | Requisitos acadêmicos considerados nesta etapa |
| `README-configuracoes-github.md` | [`.github/README.md`](https://github.com/projeto-argos/.github/blob/main/README.md) | Configurações compartilhadas da organização |
| `README-perfil-organizacao.md` | [`.github/profile/README.md`](https://github.com/projeto-argos/.github/blob/main/profile/README.md) | Apresentação pública e estrutura do ARGOS |
| `CONTRIBUTING.md` | [Guia de contribuição](https://github.com/projeto-argos/.github/blob/main/CONTRIBUTING.md) | Regras de branches, commits, revisão e merge |
| `PULL_REQUEST_TEMPLATE.md` | [Modelo de Pull Request](https://github.com/projeto-argos/.github/blob/main/PULL_REQUEST_TEMPLATE.md) | Estrutura oficial dos Pull Requests |
| `README-argos-docs.md` | [`argos-docs/README.md`](https://github.com/projeto-argos/argos-docs/blob/main/README.md) | Organização da documentação e dos artefatos |
| `README-argos-web-crud.md` | [`argos-web-crud/README.md`](https://github.com/projeto-argos/argos-web-crud/blob/main/README.md) | Estrutura da aplicação Java/Maven |
| `README-argos-bd.md` | [`argos-bd/README.md`](https://github.com/projeto-argos/argos-bd/blob/main/README.md) | Modelagem e scripts do PostgreSQL |
| `README-argos-landingpage.md` | [`argos-landingpage/README.md`](https://github.com/projeto-argos/argos-landingpage/blob/main/README.md) | Landing page e interfaces web |
| `README-argos-ai.md` | [`argos-ai/README.md`](https://github.com/projeto-argos/argos-ai/blob/main/README.md) | Documentação das aplicações de IA |

## Prioridade das informações

Em caso de conflito, o agente deverá seguir esta ordem:

1. Instruções do prompt do sistema.
2. Documentação oficial atual dos repositórios.
3. Requisitos do primeiro ano.
4. Exemplos fornecidos nas conversas.

Os requisitos do segundo ano não devem ser considerados nesta etapa.

## Manutenção

A base deverá ser revisada quando:

- Uma regra de colaboração for alterada.
- Um repositório ou caminho for criado, removido ou renomeado.
- O modelo de Pull Request for atualizado.
- O fluxo do Jira for definido ou modificado.
- Uma nova versão dos requisitos do primeiro ano for disponibilizada.

Após uma atualização, os arquivos correspondentes também deverão ser substituídos na base de conhecimento do Gem.

## Segurança

Não devem ser adicionados:

- Senhas, tokens ou credenciais.
- Arquivos `.env`.
- Dados pessoais sem autorização.
- Documentos privados ou protegidos sem permissão para compartilhamento.
- Conteúdos referentes aos requisitos do segundo ano.

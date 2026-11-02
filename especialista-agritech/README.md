# Especialista Agritech do ARGOS

Agente especializado criado como **Gem** no Gemini para apoiar a equipe do ARGOS em pesquisas técnicas, sanitárias, de mercado e de experiência do usuário sobre pecuária bovina.

## Acesso

- **Gem:** [ARGOS — Solucionador de Problemas](https://gemini.google.com/gem/1g2QTOtvX4jh5v_gnr5f3AAGxDTzhYaAq?usp=sharing)
- **Nome no Gemini:** ARGOS
- **Descrição no Gemini:** Solucionador de Problemas

## Proposta do agente

### Problema que resolve

A equipe precisa tomar decisões sobre medicamentos veterinários, períodos de carência, rastreabilidade e concorrentes sem ter formação em veterinária ou em agronegócio. Informações desse tipo mudam com a legislação e com a bula de cada produto, e um erro pode virar uma regra errada no sistema.

### Público-alvo

Os integrantes da equipe do ARGOS durante o desenvolvimento do projeto: quem define regras de negócio, quem pesquisa o mercado e quem desenha as telas.

### Objetivo principal

Transformar dúvidas técnicas, sanitárias, de mercado e de UX em informações verificadas, com fonte, e em ações práticas para o ARGOS.

### Relação com o projeto

O ARGOS registra medicamentos aplicados em bovinos e acompanha os períodos de carência. O agente apoia a definição dessas regras, a pesquisa de concorrentes (benchmark) e as decisões de UX para o uso no campo, sempre separando o que é regra oficial, o que é regra de negócio proposta e o que ainda precisa de validação.

## Estrutura do agente

| Item pedido | Onde está no prompt |
|---|---|
| Persona | Identidade e contexto |
| Instruções | Missão e Processo de trabalho |
| Comportamento esperado | Política de fontes e Estilo de comunicação |
| Limitações | Segurança veterinária e sanitária, Proteção de dados |
| Formato das respostas | Formato das respostas |
| Regras contra respostas inadequadas | Política de fontes, Segurança veterinária e Pesquisa de concorrentes |

## Limites importantes

O agente:

- Não substitui um médico-veterinário.
- Não faz diagnóstico nem prescrição.
- Não inventa períodos de carência, preços nem funcionalidades de concorrentes.
- Não apresenta sugestões como requisitos já aprovados.
- Avisa quando não encontra fontes confiáveis.

## Exemplos de perguntas

- Quais informações devem ser registradas na aplicação de um medicamento em um bovino?
- Quais dados são necessários para acompanhar um período de carência?
- Como os concorrentes apresentam o cadastro dos animais?
- Como simplificar um fluxo para uso no campo?

## Arquivos

- [Prompt de sistema](./prompt-sistema-agritech-argos.md)
- [Base de conhecimento](./base-de-conhecimento.md)

# ARGOS — Inteligência Artificial

Repositório do agente de IA criado para o ARGOS, sistema web de gestão de pecuária e de medicamentos aplicados em bovinos.

## Estrutura

```text
argos-ai/
├── especialista-agritech/
│   ├── README.md                         proposta, acesso e limites do agente
│   ├── prompt-sistema-agritech-argos.md  instruções configuradas no Gem
│   └── base-de-conhecimento.md           fontes que o agente usa
├── memorial/
│   ├── memorial-descritivo-ia.md         uso de IA no projeto (6 seções)
│   └── imagens/                          prints das evidências
└── README.md
```

## Agente

| Agente | Gem | Função |
|---|---|---|
| Especialista Agritech do ARGOS | [ARGOS — Solucionador de Problemas](https://gemini.google.com/gem/1g2QTOtvX4jh5v_gnr5f3AAGxDTzhYaAq?usp=sharing) | Apoia pesquisas técnicas, sanitárias, de mercado e de UX sobre pecuária bovina |

Mais detalhes em [`especialista-agritech/`](./especialista-agritech/).

## Memorial descritivo

O [memorial descritivo do uso de IA](./memorial/memorial-descritivo-ia.md) mostra em que etapas a equipe usou IA, as evidências com prompts e respostas, as ferramentas, como as respostas foram validadas e os cuidados com segurança e LGPD.

## Uso responsável

Todo conteúdo produzido com auxílio de IA é revisado pela equipe antes de ser usado no projeto. Não são enviados a este repositório senhas, chaves de API, arquivos `.env`, dados pessoais ou conversas com informações sensíveis.

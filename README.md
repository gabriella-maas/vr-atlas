# VR Atlas

O **VR Atlas** é um protótipo de plataforma interna criada para ajudar colaboradores a compreenderem o **VR Super** como um sistema único e conectado, e não apenas como um conjunto de módulos isolados.

A ideia do Atlas é dar contexto antes de levar a pessoa diretamente para uma tela ou documentação extensa.

Ele foi pensado para apoiar onboarding, troca de módulo, análise de regras de negócio, entendimento de fluxos, testes, suporte e refinamento de funcionalidades.

---

## Objetivo

Permitir que qualquer pessoa compreenda o VR Super como um sistema único, entendendo:

- onde cada módulo se encaixa;
- de onde o dado vem;
- para onde o dado vai;
- quais telas participam de cada processo;
- quais campos são importantes;
- quais regras de negócio existem;
- quais módulos são impactados por uma alteração.

---

## Conceito

O VR Atlas não é uma documentação tradicional.

Ele funciona como uma camada visual e contextual sobre o produto, organizando o conhecimento do ERP por fluxo, relação e impacto.

Em vez de apresentar apenas textos longos sobre cada tela, o Atlas busca responder perguntas como:

- Para que essa funcionalidade existe?
- Quem usa?
- Quando usa?
- O que vem antes?
- O que acontece depois?
- Quais campos importam?
- Quais regras precisam ser respeitadas?
- O que pode quebrar se algo mudar?

---

## Público-alvo

O VR Atlas foi pensado para diferentes perfis dentro da empresa:

- novos colaboradores em onboarding;
- QAs que precisam entender fluxo, risco e regressão;
- POs que precisam refinar regras e critérios de aceite;
- suporte que precisa entender dúvidas e impactos;
- desenvolvedores que precisam compreender comportamento esperado;
- colaboradores que mudaram de módulo ou squad;
- qualquer pessoa que precise entender melhor o VR Super.

---

## Funcionalidades do protótipo

O protótipo atual contém:

- tela inicial institucional;
- fluxo macro de operação de supermercado;
- seleção de lente/view por perfil;
- navegação lateral entre módulos;
- telas de módulos do VR Super;
- detalhamento de funcionalidades;
- campos importantes;
- regras de negócio;
- ciclo de vida das operações;
- mapa de impacto;
- conteúdo adaptado por lente, como QA, PO, Suporte, DEV e Novo Colaborador.

---

## Lentes / Views

O Atlas permite visualizar a mesma funcionalidade por diferentes perspectivas:

### Novo Colaborador

Foco em contexto, glossário, conceitos básicos e entendimento geral do fluxo.

### QA

Foco em riscos, cenários de teste, regressão, campos críticos e perguntas para PO.

### PO

Foco em regras de negócio, critérios de aceite, dependências e decisões pendentes.

### Suporte

Foco em dúvidas comuns, erros recorrentes, causas prováveis e onde consultar.

### DEV

Foco em comportamento esperado, dependências funcionais, integrações e impactos técnicos.

---

## Estrutura do protótipo

O projeto está em HTML, CSS e JavaScript puro.

Estrutura esperada do repositório:

```txt
vr-atlas/
└── index.html

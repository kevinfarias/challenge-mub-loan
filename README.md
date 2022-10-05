<img src="img/mub.darkblue.png" alt="drawing" style="width:200px;"/>

----------

# AKQUINET HKS - MUB TEAM - CODE CHALLENGE

## Objetivo

O Objetivo desse desafio é avaliar o conhecimento e capacidade dos candidatos às vagas de programação/desenvolvimento frontend/fullstack do time mub.

## Instruções

1. Crie um repositório para o versionamento do seu projeto no github.
2. Siga a instruções de desenvolvimento.
3. Coloque um readme.md no projeto explicando como instalar e rodar o projeto.
4. Convide o usuario @kevinfarias para o repositório.
5. Envie o link do repositório para o email: kevin.farias@mub.one

## O que deve ser desenvolvido

Uma aplicação web que traga uma calculadora de financiamento, onde facilmente o usuário pode preencher o valor do financiamento, valor de entrada, numero de meses e taxa de juros, e logo após, clicar em um botão de calcular que trará em tela o valor de cada parcela.

### Regras de negócio

1. O sistema de amortização à ser utilizado é o sistema PRICE. Para validação, você pode usar como consulta esta calculadora online gratuita: [Calculadora PRICE Online](https://www.calculadora.com.br/financeira/financiamento-price/). Como material de apoio, o calculo está explicado de forma didática no seguinte vídeo: [Video explicação PRICE](https://www.youtube.com/watch?v=iESlw6pz1fQ). Porém, existem diversos materiais na internet que auxiliam no entendimento do mesmo.
2. O máximo de parcelas que podem ser digitadas é de 100.
3. Os juros mensais não podem passar de 5%.
4. Para fins de facilidade, a primeira parcela é sempre o dia primeiro do próximo mes. As demais, são subsequentes (uma parcela cada mês - sempre no mesmo dia)
5. A tabela de parcelas deve mostrar: Número da parcela / Data de pagamento / Valor / Juros / Amortização / Saldo Devedor

## Requisitos técnicos

O teste precisa ser aplicado utilizado o framework Angular v10+ e os cálculos podem ser resolvidos tanto no backend ou frontend.
Não é obrigatório criar uma API backend para este teste, porém se a vaga é fullstack, é obrigatório que o teste seja desenvolvido utilizando backend (com laravel) e frontend (com angular).
Podem ser usados qualquer tipo de lib CSS (Material UI, Bootstrap, Tailwind, etc), mas se não utilizar, será considerado um ponto positivo pois demonstrará a habilidade do candidato com CSS.

Torne o projeto fácil de ser executado (crie um passo a passo e/ou utilize docker).

## O que será avaliado

- Qualidade do código
- Componentização e reutilização de código
- Versionamento correto
- Testes (não é obrigatório - mas se fizer será considerado positivamente)
- Regra de negócio condizente com o solicitado.

## Dicas

- Prefira funções puras
- Use gitflow e escreva comentários claros e objetivos em cada commit (o uso de commits semânticos é bem visto)
- O uso de eslint, editor config, docker, webpack, etc facilitam sua vida
- Lembre-se do conceito de DRY e aplique
- Se possível, escreva o código em inglês, pois esse é o padrão utilizado na empresa.

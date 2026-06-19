# Copilot Cowork Credit Calculator

Calculadora estatica da NEIVA Cloud Solutions para estimar o consumo mensal e anual de Copilot Credits em cenarios de Cowork, alem de comparar custo de pay-as-you-go com os niveis do Plano de Pre-Compra de Creditos (P3).

Site publicado: https://felipeneivadc.github.io/copilot-cowork-credit-calculator/

## O que a pagina faz

- Estima consumo de creditos por perfil de usuario.
- Permite ajustar quantidade de usuarios, prompts e creditos por tipo de prompt.
- Calcula orcamento mensal/anual em USD.
- Compara o custo liquido dos 9 niveis P3.
- Destaca automaticamente a opcao mais economica para o consumo informado.
- Permite gerar PDF pela janela de impressao do navegador.

## Base Microsoft

Esta calculadora foi criada pela NEIVA Cloud Solutions como uma adaptacao independente baseada em uma calculadora oficial da Microsoft para estimativas de Cowork/Copilot Credits, incluindo referencias ao Customer Cowork Estimator e aos niveis do Copilot Credit Pre-Purchase Plan (P3).

Este projeto nao e afiliado, patrocinado, aprovado ou endossado pela Microsoft. Microsoft, Copilot, Copilot Studio, Azure, Power Platform e nomes relacionados pertencem aos seus respectivos proprietarios.

## Estrutura

```text
.
├── index.html
├── assets/
│   └── logo.png
├── .gitignore
├── .nojekyll
├── LICENSE
└── README.md
```

## Publicacao

Este projeto nao precisa de build. Ele e publicado como site estatico pelo GitHub Pages usando a branch `gh-pages`, com os arquivos servidos diretamente a partir da raiz.

O arquivo `.nojekyll` informa ao GitHub Pages para nao processar o site com Jekyll.

## Privacidade do repositorio

Materiais locais usados como referencia durante a construcao, como o kit de marca, ficam ignorados pelo Git e nao devem ser commitados.

Antes de publicar alteracoes, confira:

```powershell
git status --short --ignored
git ls-tree -r --name-only HEAD
```

## Aviso

Os valores exibidos sao estimativas para apoio a planejamento. Eles nao substituem validacao comercial, contratual ou tecnica com fontes oficiais da Microsoft, contratos vigentes e dados reais da organizacao.

## Licenca

Consulte o arquivo `LICENSE`.
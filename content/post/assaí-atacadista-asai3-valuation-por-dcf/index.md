---
title: Assaí Atacadista (ASAI3) - Valuation por DCF
date: 2021-05-11T00:00:00Z
draft: false
featured: false
authors:
  - admin
tags:
  - Valuation
  - DCF
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
<div align="justify">

### Metodologia de valuation

Para chegar no valor justo para o Assaí Atacadista usei um modelo de desconto de fluxo de caixa (DCF)  com 3 etapas:

* Etapa de crescimento acelerado de 2021 até 2025;
* Etapa de redução da taxa de crescimento de 2026 até 2030;
* Etapa de crescimento estável a partir de 2031.

Utilizei uma taxa livre de risco de 5,43% a.a., obtida a partir da soma da expectativa de inflação no LP (de 4%) com a taxa real de 3,91% da [NTN-B Principal](https://www.tesourodireto.com.br/titulos/precos-e-taxas.htm), subtraída do prêmio de risco para o governo brasileiro com base no seu rating ([Ba2](https://www.moodys.com/credit-ratings/Brazil-Government-of-credit-rating-114650/reports?category=Ratings_and_Assessments_Reports_rc|Issuer_Reports_rc&type=Rating_Action_rc|Announcement_rc|Announcement_of_Periodic_Review_rc,Credit_Opinion_ir_rc|Issuer_Comment_rc|Issuer_in_Depth_rc)/BB) de [2,53%](https://fred.stlouisfed.org/series/BAMLH0A1HYBB). (Valores do início de março/2021)

Para o Prêmio de Risco para Equities (Equity Risk Premium - ERP) utilizei o valor de 7,63%, calculado com base no ERP implícito de um mercado maduro (nesse caso, os EUA) de [4,72%](http://pages.stern.nyu.edu/~adamodar/) somado ao Prêmio de Risco do País (Country Risk Premium - CRP) de 2,91%, obtido a partir da multiplicação do prêmio de risco para os títulos do governo (Ba2/BB) pela volatilidade relativa do Ibovespa em relação à volatilidade dos títulos públicos.

Para o beta da empresa, foi utilizado o valor de 0,47 para o beta desavalancado (sem o efeito da dívida), equivalente à media do setor nos EM. Levando em conta a dívida, o beta é de 0,55. Isso faz com que o Custo de Capital Próprio (Cost of Equity) seja igual a 9,6%, e, levando em consideração o rating BB para a empresa e o seu spread de risco associado, temos um custo da dívida após impostos de 5,41%. Ponderando esses custos, temos um WACC de 8,76% para a empresa no médio prazo. (Na fase de crescimento estável diminuo o WACC para 8%, assumindo a ocorrência de diminuições na taxa livre de risco).

### A história

O Assaí é uma empresa que pertencia ao Grupo Pão de Açúcar mas que recentemente se desvinculou da holding. O modelo de negócios da firma é baseado no "atacarejo" - mescla entre atacado e varejo, porém buscando atender ao consumidor pessoa física - com preços baixos, grande volume de vendas e relativa variedade de produtos. 

A pandemia não afetou muito esse modelo de negócio, sendo refletido numa expansão ano a ano de quase 30% da receita bruta em 2020. Esse caminho de crescimento deve continuar por algum tempo - fato que já foi sinalizado pela empresa no seu último informe de resultados, buscando inaugurar 80 lojas até 2023 -, até que atinja uma boa participação no *Market Share* de atarejos e de supermercados em geral, após isso, ele deve crescer à taxa de crescimento da economia. No momento a empresa representa 29% do mercado de atacarejo e 9,5% do mercado de supermercados em geral.

Contudo, esse crescimento fatalmente virá acompanhado de uma redução da margem operacional (margem EBIT(1-t)) devido à competição no setor e o processo fidelização do consumidor. Essa redução é parcialmente balanceada por um aumento de eficiência logística com a grande expansão em nível nacional. 

Um ponto positivo é que a empresa não sofre por grandes necessidades de reinvestimento, tendo um giro de ativos alto, ligeiramente maior que a média do setor para mercados emergentes. Além disso, a empresa possui um retorno sobre o capital alto, que convergirá para a média setorial (10%) até a fase de crescimento estável.

Tudo isso me leva a crer que a empresa crescerá 20% em 2021 (com a abertura planejada de lojas pela empresa e menos crescimento nas lojas existentes) e terá um CAGR de 15% entre 2022 e 2025. Após isso ela deve convergir para a taxa de crescimento da economia no longo prazo de 5%. Isso a deixa com um Market Share de 50% e de 20%, para os setores de atacarejo e supermercados em geral, respectivamente.

<div align="center">{{< figure src="1.png" caption="Market Share atual e projetado" >}}</div>

Resumindo, as perspectivas elaboradas para a empresa estão representadas no quadro abaixo:

<div align="center">{{< figure src="2..png" caption="Perspectivas da empresa" >}}</div>

### A valuation

Com base nesses parâmetros, chega-se a um valor para a ação de R$ 97,87. Um *upside* potencial de 27% em relação aos preços do dia 25/03/21. 

Tendo elaborado a história para a empresa, segue, agora, o modelo completo de valuation. Se quiser mudar algum parâmetro, ou refazer a valuation do seu próprio jeito, é só clicar [nesse link](https://docs.google.com/spreadsheets/d/16f4XgydPM4SvpAGBZYGaxpmQXiLPDWGtS8wNZbRg6Ns/edit?usp=sharing), que abrirá uma planilha no Google Sheets. Caso prefira, a planilha que eu usei também está disponível no site do [Aswath Damodaran](http://pages.stern.nyu.edu/~adamodar/).

<div align="center">{{< figure src="3..png" caption="Output completo do modelo" >}

Obrigado pela atenção! </div></div>

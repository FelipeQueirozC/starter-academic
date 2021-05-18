---
title: Banco do Brasil (BBAS3) - Valuation por DDM
date: 2021-03-08T10:30:01.015Z
draft: false
featured: false
authors:
  - admin
tags:
  - Valuation
  - DDM
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
<div align="justify">

Para avaliar o valor justo por ação do Banco do Brasil, utilizei um modelo de desconto de dividendos (DDM), com crescimento acelerado por 2 anos (2021 e 2022).

Utilizei uma taxa livre de risco de 5,43% a.a., obtida a partir da soma da expectativa de inflação no LP (de 4%) com a taxa real de 3,91% da [NTN-B Principal](https://www.tesourodireto.com.br/titulos/precos-e-taxas.htm), subtraída do prêmio de risco para o governo brasileiro com base no seu rating ([Ba2](https://www.moodys.com/credit-ratings/Brazil-Government-of-credit-rating-114650/reports?category=Ratings_and_Assessments_Reports_rc|Issuer_Reports_rc&type=Rating_Action_rc|Announcement_rc|Announcement_of_Periodic_Review_rc,Credit_Opinion_ir_rc|Issuer_Comment_rc|Issuer_in_Depth_rc)/BB) de [2,53%](https://fred.stlouisfed.org/series/BAMLH0A1HYBB). (Valores do início de março/2021)

Para o Prêmio de Risco para Equities (Equity Risk Premium - ERP) utilizei o valor de 7,67%, calculado com base no ERP implícito de um mercado maduro (nesse caso, os EUA) de [4,71%](http://pages.stern.nyu.edu/~adamodar/) somado ao Prêmio de Risco do País (Country Risk Premium - CRP) de 2,91%, obtido a partir da multiplicação do prêmio de risco para os títulos do governo (Ba2/BB) pela volatilidade relativa do Ibovespa em relação à volatilidade dos títulos públicos.

Além disso, utilizei como dividendo base o valor de R$1,48 por ação ON (BBAS3) em 2020 e o LPA (EPS) de R$4,37 em 2020.

O beta utilizado foi de 1,1, mais arriscado do que a média setorial dos mercados emergentes para o setor bancário, refletindo os riscos da interferência pública no management do BB. Contudo, há de se considerar o cenário de privatização, em que o beta cairia para 0,95, em linha com a média setorial.

Obtemos, assim, o custo do patrimônio líquido (Cost of Equity) de 13,87%, somando a taxa livre de risco ao ERP multiplicado pelo beta. Caso ocorra a privatização, esse valor cairia para 12,72%.

Para o ROE (Retorno sobre o patrimônio líquido) na fase de crescimento foi usado o valor de 12% (menor que a média histórica, mas mais alto que o valor de 2020), provocada por um provável aumento na taxa SELIC no CP, junto com um *payout* de 45%. Com isso, obtemos uma taxa de crescimento de 6,6% do LL em 2021 e 2022.

O crescimento estável do Lucro Líquido é de 5,20% (um pouco menor que a taxa de crescimento da economia, refletindo um aumento da competição no setor bancário). Já o ROE no crescimento estável é de 14% (ligeiramente menor que a média histórica, fundamentado por aumentos no MP da taxa SELIC, mas não a níveis como os de 2015-16). Com esses dados, calcula-se o payout de 62,86% na perpetuidade.

O Resultado da valuation nos dá um valor por ação de R$32,79 para o caso sem privatização e R$37,26 com privatização em 2021/22, após o período de crescimento acelerado. Assumindo a probabilidade da privatização ocorrer for de 20%, temos um valor por ação de R$33,68, ou seja, um upside potencial de 10,9%, aproximadamente, em relação ao preço atual. 

</div>

<div align="center">{{< figure src="1.png" caption="Upside potencial" >}}</div>

<div align="justify">

Segue abaixo o output total do modelo DDM, e, caso você mesmo queira mudar algum parâmetro do modelo, a planilha que eu usei está disponível no site do [Aswath Damodaran](http://pages.stern.nyu.edu/~adamodar/), mas, também pode baixar ela, juntamente com os parâmetros que eu usei, [nesse link](https://drive.google.com/file/d/1UrPxO0Oms7cGZbFF5aMv8MxnIiXN6bGM/view?usp=sharing).

</div>

<div align="center">

{{< figure src="2..png" caption="Output completo do modelo" >}}

Obrigado pela atenção! 

</div>
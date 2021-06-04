# Causality relationships among the Vale's stocks return, macroeconomic indicators and environmental disasters


## About

<div align="justify"> We can observe the importance of Vale's shares in Ibovespa (Brazilian Financial Market) by its weight in the composition of this index,
corresponding to approximately 10%. The financial market is directly linked to the development of a country since this market attracts resources to companies, 
thus providing investment and jobs. In this regard, it is essential to understand how Vale's stock return relates to macroeconomic indicators and whether they have a causal 
relationship between them.</div>


<div align="justify">Furthermore, it's equally important to investigate the relationship between Vale's shares and the occurrence of environmental accidents involving mining activities, such as the 
dam's rupture in Córrego do Feĳão Mine, in Brumadinho (MG), on January 25, 2019, and the accident in Bento Rodrigues dam (Fundão), in Mariana (MG), on November 5, 2015.</div>

<div align="justify">In this project, I apply the Auto-Regressive Vectors (VAR) model, which presents the relationship among the returns of Vale's shares, the macroeconomic indicators widely used in 
the literature, the price of iron ore on the spot market, and environmental accidents involving the mining sector. The central question to be answered is whether it is possible to 
predict the return on Vale's assets using information recorded from economic aggregates, the iron ore price, and the environmental accidents caused by mining companies. For this 
project, the analysis period comprises the months of April 2002 to November 2019.</div>

<div align="justify">The results show that the return on Vale's stock is negatively related to its volatility, while the iron ore price and Ibovespa lagged by one month have positive coefficients 
relating to Vale's returns. In addition, this project does not indicate that environmental accidents, caused by mining companies, impact Vale's stock return in the long run.</div>

<div align="justify">This project contributes by using a time series analysis to study the relationship among macroeconomic indicators, iron ore spot price, accidents caused by mining companies, and 
Vale's shares volatility since no other project investigates the long-term relationship of the variables included in this project.</div>

## Methodology

- Vector autoregression (VAR)
- Impulse Response Function (IRF)
- Variance Decomposition of Forecast Errors

## Technology

RStudio (R programming language)

## Libraries

- aTSA
- BatchGetSymbols
- forecast
- readxl
- tseries 
- urca
- vars

## Source

The dataset was extracted in the sources below:

- [Yahoo Finance](https://finance.yahoo.com/)
- [Central Bank of Brazil](https://www4.bcb.gov.br/pec/series/port/aviso.asp?frame=1)

##

Developed by [Thiago Balbo](https://github.com/ThiagoBalbo16)

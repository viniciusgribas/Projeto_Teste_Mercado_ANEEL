# Projeto_Preditivo_Mercado_Energia_ANEEL
Análise exploratória sobre a tarifa aplicada para unidades consumidoras de energia elétrica no brasil. Com os dados de fornecimento e consumo das distribuidoras por nível de tensão, disponibilizados via CSV e XLSX pela ANEEL. Foi possível realizar uma visualização em gráficos de barras sobre as maiores tarifas em energia elétrica para uma classe específica. O consumidor B1 (Residencial). É um resultado simples, fruto de aplicações das bibliotecas Pandas, Numpy e Sklearn para prever possíveis tarifas. 


ANÁLISE EXPLORATÓRIA UTILIZANDO DADOS DE MERCADO SAMP¶
DICIONÁRIO DE DADOS:
Os dados foram extraídos dos relatórios de consumo e receita de distribuição através do link: ( https://www.aneel.gov.br/relatorios-de-consumo-e-receita ). <Acesso em 9 de setembro de 2021.>

Ano: ano de coleta dos dados, variando entre 2003 a 2021.

Mes: mes da coleta dos dados, variando entre 01 e 12.

DessClasseConsumo: tipologia da classe de consumo, variando entre: Comecial, Industrial, Rural, etc..

NomeAgente: Distribuidoras de energia elétrica do Brasil.

FaixaTensao: Nivel de tensão das unidades consumidoras.

ConsumoEnergiaEletricaMWh: Consumo aferido no período em questão.

ReceitaFornecimentoEE: Receita em Reais do consumo: (Consumo * Tarifa).

NumeroUnidadesConsumidoras: Unidades consumidoras da classe e nível de tensão;

ReceitaFornecimentoEEImp: Receita + Impostos em Reais do Consumo: (Consumo * TarifaImp).

TarifaMediaFornecimento: Multiplicador tributário para valorar o consumo; e

TarifaMediaFornecimentoImp: Multiplicador tributário para valorar o consumo, com impostos.

DataUltAtu: Data da ultima atualização dos dados utilizados.

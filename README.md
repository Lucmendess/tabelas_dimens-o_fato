# tabelas_dimens-o_fato


Para criar um modelo de star schema a partir da tabela única de Financial Sample, você precisará identificar as dimensões e a tabela fato.
As tabelas dimensão fornecem o contexto para as métricas na tabela fato. A partir da tabela Financial Sample.
Estabelecendo os relacionamentos entre as tabelas.
Após a construção do modelo, você pode realizar consultas que envolvam métricas como vendas totais por produto, por período ou por cliente, utilizando as dimensões como filtros.

Algumas das funções DAX:
Média_Unidades_Vendidas = AVERAGE(F_Vendas[Units Sold])

Mês = FORMAT(D_Calendário[Data], "MMMM")

Ano = YEAR(D_Calendário[Data])

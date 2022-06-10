# Teste técnico - Eng. de Dados (MINEHR)

 > Candidato: Flávio Macaúbas Torres Filho
 
 > **OBSERVAÇÃO: REPRODUZIR O CÓDIGO NO DATABRICKS PERMITE UMA VISUALIZAÇÃO MELHOR DOS DATAFRAMES, A FUNÇÃO display(...) NÃO FORMATA ADEQUADAMENTE NO GIT**

### Dados originais

* Disponíve aqui: [Dados](https://github.com/FlavioMacaubas/desafio_minerh/blob/master/base_mensalizada_de_funcionarios.csv)

### Dados após ajustes

* Podem ser acessados aqui: [Dados](https://community.cloud.databricks.com/?o=1934713391467732#table/default/base_mensalizada_de_funcionarios_csv)
  + Necessita login no DataBricks

* Alternativamente: [Github](https://github.com/FlavioMacaubas/desafio_minerh/blob/master/dados_finais.csv)


### Conclusões Preliminares

* Foram perdidas 16 observações (13,2%) nas etapas solicitadas;

* A etapa de categorização do Grau de Instrução foi antecipada dado as especificações do item 4 do 1º Passo.

* Foi percebido uma incosistência entre Mês Referência e Data de Admissão na etapa de transformação.

  + Recomendação: a checagem da data de admissão do funcionário 24457
  
### Insights Preliminares

* A idade média dos colaboradores é de 35 anos

* O tempo de empresa médio é de 117 meses - aproximadamente 10 anos

* A média salarial é de aproximadamente R$ 5000,00

* Houve 9 mudanças salariais

* Houve 2 mudanças de cargos

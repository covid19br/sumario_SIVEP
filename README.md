# Sumário SIVEP

Repositório com dados agregados para cada base de dados da SIVEP.

Cada arquivo corresponde a uma base de dados SIVEP-Gripe pública. A data da base está contida no nome do arquivo, e cada arquivo tem a seguinte estrutura:

| coluna | dt_evento | age_class | co_mun_res | sg_uf | srag | covid | ob.srag | ob.covid |
| ------ | --------- | --------- | ---------- | ----- | ---- | ----- | ------- | -------- |
| tipo   | data      | string (age_NN) | num  | string | num | num   | num     | num      |
| descrição | data do evento (de primeiros sintomas para hospitalizações, de óbito para óbitos) | faixa etária (de 10 em 10 anos) | geocode IBGE do município de residência | sigla do estado | número de hospitalizações por SARI | número de hospitalizações por SARI-Covid | número de óbitos por SARI | número de óbitos por SARI-Covid |


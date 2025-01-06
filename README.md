# Desigualdade em Saúde no Brasil utilizando modelo do HEAT/WHO

** Bloco 1 - Mortalidade com dados do SIM/SUS e dos Censos de 2010 e 2022

A mortalidade é calculada por 100.000 habitantes, com o filtro de causas evitáveis.

O arquivo 'heatds_mort_uf_mun_sexocor.xlsx' é o primeiro dataset que iremos construir e tem as seguintes características:

* setting: UF
* dimension: município
* subgroup: sexo + raça-cor



Estas escolhas implicam em podermos disponibilizar ao usuário do HEAT a possibilidade de ver os municípios (dimensões) de maneira agregada por UF. Caso não fosse assim, sempre seriam mostrados todos de uma vez.
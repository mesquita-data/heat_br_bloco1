# Desigualdade em Saúde no Brasil utilizando modelo do HEAT/WHO

** Objetivos

O principal objetivo desse projeto é realizar a avaliação de desigualdade na saúde no Brasil com ênfase para a dimensão de unidades subnacionais, estados e municípios brasileiros, a partir da aplicação do modelo do HEAT, tendo como objetivos específicos:

- Apresentar indicadores de saúde no Brasil desagregados por subunidades nacionais em uma visualização interativa a partir do modelo do HEAT Plus;
- Oferecer um repositório comum e atualizado com dados de desigualdade da saúde no Brasil desagregados por estados e municípios em um modelo sob reconhecimento internacional;
- Permitir exploração e acesso dos dados e da metodologia para outros tipos de análises.

O HEAT é um modelo de dados elaborado pela Organização Mundial da Saúde voltado a apresentar diversos indicadores, organizados por um conjunto muito amplo de datasets que reúnem variáveis e indicadores, reunindo dados de todo o mundo.

O HEAT + é uma versão do HEAT passível de ser intalada localmente e, a partir do modelo de dados, também permitir a instituições e pesquisadores apresentar facilmente novoso conjuntos de dados relacionando indicadores e variáveis que apresentam desigualdade em saúde.

** Blocos do Projeto

As entregas deste projeto ocorrerá em blocos, trimestrais.

Para cada bloco, realizado de maneira em conjunta pelo Ministério da Saúde e pela OMS, será definido um tema, um ou mais indicadores relacionados ao tema e a elaboração de datasets que possam utilizar o HEAT+ para exibição de dados. Sempre relativos à desigualdade em saúde.

*** Bloco 1 - Mortalidade com dados do SIM/SUS e dos Censos de 2010 e 2022

Para o primeiro trimestre de 2025 está definido que o tema é mortalidade e serão entregues datasets relacionados a indicadores de mortalidade evitável.

Os óbitos serão calculados a partir dos dados extraídos do SIM/SUS, Sistema de Informação de MOrtalidade que reúne dados de óbitos de todo o Brasil, gerenciado de maneira colaborativa pelas secretarias municipais, estaduais e Ministério da Saúde.

A mortalidade é calculada por 100.000 habitantes, com o filtro de causas evitáveis.

- indicador: mortalidade (número de mortes por população, dados de morte do SIM/SUS e dados populacionais pelo Censos de 2010 e 2022)
- localização: todo o Brasil, com agregação de mortalidade por Estados e Municípios (a depender do dataset)
- período: 2010 e 2022 
- doenças: “doenças evitáveis” conforme definido pelo OCDE
- outros critérios de filtro: até 74 anos de idade (em razão da aplicação do critério de "doenças evitáveis")

** Organização do projeto no git.

Cada bloco terá um repositório próprio.

O repositório do bloco 1 está organizado da seguintes forma:
- arquivo com extração de dados do SIM: Dados Comuns
- datasets apresentados de acordo com as principais variáveis selecionados conforme modelo do HEAT+ (os arquivos começam com AvoidMort_ds ...)
- pastas que reúnem bases originais ou em transformação
-- files_in_sim = dowload de arquivos de dados brutos do SIM
-- files_in_geral = download de arquivos auxiliares para o projeto
-- files_temp = arquivos temporários e de etapas de transformação do projeto
-- files_out = arquivos finais do projeto, para exportação e carga no HEAT+




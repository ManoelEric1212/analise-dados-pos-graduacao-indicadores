# Relatório Analítico PPGEEC

**Gerado em:** 24/03/2026 17:59:19

## 1. Resumo executivo

Este relatório consolida a análise multianual das produções do PPGEEC, com foco na qualidade da ingestão,
na cobertura dos identificadores bibliográficos, no enriquecimento com Qualis e nos indicadores DPI e PR.

Foram analisadas 183 produções únicas ao longo do período 2021–2024.
A cobertura de ISSN consolidada foi de 28.96%,
enquanto a cobertura de Qualis atingiu 25.14%.
A cobertura do identificador esperado, inferida a partir do tipo/subtipo da produção, ficou em
35.52%.

As tabelas finais incluem a visão consolidada de docentes e programa, bem como a visão anual,
permitindo acompanhar a evolução dos indicadores e identificar gargalos de cobertura e classificação.

## 2. Indicadores gerais

| Indicador                    | Valor     |
|:-----------------------------|:----------|
| Produções únicas             | 183       |
| Docentes com produção        | 19        |
| Período analisado            | 2021–2024 |
| Produções com ISSN           | 53        |
| Produções com Qualis         | 46        |
| % com ISSN                   | 28.96     |
| % com Qualis                 | 25.14     |
| % com identificador esperado | 35.52     |

## 3. Cobertura de ISSN por produção

### 3.1 Cobertura consolidada

|   producoes_totais |   producoes_com_issn |   producoes_sem_issn |   cobertura_issn_pct |
|-------------------:|---------------------:|---------------------:|---------------------:|
|                183 |                   53 |                  130 |                28.96 |

### 3.2 Gráfico

![Cobertura de ISSN por ano](grafico_cobertura_issn_por_ano.png)

### 3.3 Cobertura por ano

|   ano |   producoes_totais |   producoes_com_issn |   producoes_sem_issn |   cobertura_issn_pct |
|------:|-------------------:|---------------------:|---------------------:|---------------------:|
|  2021 |                 68 |                   27 |                   41 |                39.71 |
|  2022 |                 34 |                   12 |                   22 |                35.29 |
|  2023 |                 42 |                    7 |                   35 |                16.67 |
|  2024 |                 39 |                    7 |                   32 |                17.95 |

## 4. Cobertura do identificador esperado

A cobertura abaixo é inferida a partir do tipo/subtipo da produção. A regra usada foi:

- **ISSN** para artigos/periódicos/revistas
- **ISBN** para livros/capítulos/e-books
- **DOI** para trabalhos em anais/eventos quando aplicável

### 4.1 Cobertura por tipo inferido

| identificador_esperado   |   producoes_totais |   com_identificador |   sem_identificador |   cobertura_pct |
|:-------------------------|-------------------:|--------------------:|--------------------:|----------------:|
| DOI                      |                 99 |                   0 |                  99 |            0    |
| ISBN                     |                 12 |                  12 |                   0 |          100    |
| ISSN                     |                 54 |                  53 |                   1 |           98.15 |
| OUTRO                    |                 18 |                   0 |                  18 |            0    |

![Cobertura do identificador esperado por tipo](grafico_cobertura_identificador_tipo.png)

### 4.2 Cobertura por estrato e tipo inferido

| estrato_relatorio   | identificador_esperado   |   producoes_totais |   com_identificador |   sem_identificador |   cobertura_pct |
|:--------------------|:-------------------------|-------------------:|--------------------:|--------------------:|----------------:|
| A1                  | ISSN                     |                 18 |                  18 |                   0 |           100   |
| A2                  | ISSN                     |                  3 |                   3 |                   0 |           100   |
| A3                  | ISSN                     |                 14 |                  14 |                   0 |           100   |
| A4                  | ISSN                     |                  8 |                   8 |                   0 |           100   |
| B1                  | ISSN                     |                  1 |                   1 |                   0 |           100   |
| B3                  | ISSN                     |                  1 |                   1 |                   0 |           100   |
| B4                  | ISSN                     |                  1 |                   1 |                   0 |           100   |
| SEM_QUALIS          | DOI                      |                 99 |                   0 |                  99 |             0   |
| SEM_QUALIS          | ISBN                     |                 12 |                  12 |                   0 |           100   |
| SEM_QUALIS          | ISSN                     |                  8 |                   7 |                   1 |            87.5 |
| SEM_QUALIS          | OUTRO                    |                 18 |                   0 |                  18 |             0   |

## 5. Distribuição por estrato Qualis

| estrato    |   n_producoes |
|:-----------|--------------:|
| SEM_QUALIS |           137 |
| A1         |            18 |
| A3         |            14 |
| A4         |             8 |
| A2         |             3 |
| B4         |             1 |
| B1         |             1 |
| B3         |             1 |

![Distribuição por estrato](grafico_distribuicao_estratos.png)

### 5.1 Distribuição por ano

|   Ano da Produção | estrato    |   n_producoes |
|------------------:|:-----------|--------------:|
|              2021 | A1         |            14 |
|              2021 | A3         |             9 |
|              2021 | A4         |             2 |
|              2021 | B4         |             1 |
|              2021 | SEM_QUALIS |            42 |
|              2022 | A1         |             4 |
|              2022 | A2         |             1 |
|              2022 | A3         |             1 |
|              2022 | A4         |             2 |
|              2022 | SEM_QUALIS |            26 |
|              2023 | A2         |             1 |
|              2023 | A3         |             2 |
|              2023 | A4         |             3 |
|              2023 | B1         |             1 |
|              2023 | SEM_QUALIS |            35 |
|              2024 | A2         |             1 |
|              2024 | A3         |             2 |
|              2024 | A4         |             1 |
|              2024 | B3         |             1 |
|              2024 | SEM_QUALIS |            34 |

## 6. Transformações e detalhamento do pipeline

### 6.1 O que foi feito com as colunas e entidades

| Etapa                   | Descrição                                                                                                                                        |
|:------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------|
| Separação lógica        | A base consolidada foi separada em produções, autorias e detalhamentos para preservar a granularidade correta.                                   |
| Pivot dos detalhamentos | Os detalhamentos em formato long foram pivotados para que atributos como ISSN/DOI virem colunas analíticas.                                      |
| Enriquecimento Qualis   | As produções foram enriquecidas com Qualis usando ISSN como chave principal; quando aplicável, o estrato informado pode ser usado como fallback. |
| Cálculo de indicadores  | Foram calculados os créditos ponderados por produção e distribuídos entre docentes para DPI e PR.                                                |
| Consolidação multianual | As saídas consolidadas e por ano foram organizadas em tabelas finais para docentes e programa.                                                   |

### 6.2 Exemplo de produções após tratamento

| id_producao                                                                                                                                                                                        | Título da Produção                                                                                                                        |   Ano da Produção | Tipo da Produção   | Subtipo da Produção   | ISSN      |          ISBN | QUALIS   |   pontuacao_qualis |   n_docentes_autores | arquivo_origem   |   ano_arquivo |
|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------|------------------:|:-------------------|:----------------------|:----------|--------------:|:---------|-------------------:|---------------------:|:-----------------|--------------:|
| 22001018081P2||2021||A FRAMEWORK FOR RADIO RESOURCE ALLOCATION AND SDMA GROUPING IN MASSIVE MIMO SYSTEMS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                       | A FRAMEWORK FOR RADIO RESOURCE ALLOCATION AND SDMA GROUPING IN MASSIVE MIMO SYSTEMS                                                       |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 2169-3536 | nan           | A3       |               0.75 |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||A SEMI-DISTRIBUTED APPROACH FOR UPLINK MAX-MIN ENERGY EF-CIENCY OPTIMIZATION WITH MINIMUM USER SATISFACTION AND ADJACENCY CONSTRAINTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO     | A SEMI-DISTRIBUTED APPROACH FOR UPLINK MAX-MIN ENERGY EF-CIENCY OPTIMIZATION WITH MINIMUM USER SATISFACTION AND ADJACENCY CONSTRAINTS     |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 1980-6604 | nan           | A4       |               0.6  |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||AERIAL RECONFIGURABLE INTELLIGENT SURFACE-AIDED WIRELESS COMMUNICATION SYSTEMS||BIBLIOGRÁFICA||TRABALHO EM ANAIS                                                              | AERIAL RECONFIGURABLE INTELLIGENT SURFACE-AIDED WIRELESS COMMUNICATION SYSTEMS                                                            |              2021 | BIBLIOGRÁFICA      | TRABALHO EM ANAIS     | nan       | nan           | nan      |               0    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||ANALYSIS OF ASYMMETRIC DUAL-HOP ENERGY HARVESTING-BASED WIRELESS COMMUNICATION SYSTEMS IN MIXED FADING ENVIRONMENTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                       | ANALYSIS OF ASYMMETRIC DUAL-HOP ENERGY HARVESTING-BASED WIRELESS COMMUNICATION SYSTEMS IN MIXED FADING ENVIRONMENTS                       |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 2473-2400 | nan           | A1       |               1    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||ANÁLISE COMPARATIVA DA INFLUÊNCIA DE OTIMIZADORES NO DESEMPENHO DE UMA CNN PARA DETECÇÃO DO CÂNCER DE MAMA||BIBLIOGRÁFICA||TRABALHO EM ANAIS                                  | ANÁLISE COMPARATIVA DA INFLUÊNCIA DE OTIMIZADORES NO DESEMPENHO DE UMA CNN PARA DETECÇÃO DO CÂNCER DE MAMA                                |              2021 | BIBLIOGRÁFICA      | TRABALHO EM ANAIS     | nan       | nan           | nan      |               0    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||ANÁLISE DE REDES NEURAIS CONVOLUCIONAIS E TÉCNICAS DE PRÉ-PROCESSAMENTO PARA IDENTIFICAÇÃO DE DENTES SEROTINOS COM CISTOS||BIBLIOGRÁFICA||TRABALHO EM ANAIS                   | ANÁLISE DE REDES NEURAIS CONVOLUCIONAIS E TÉCNICAS DE PRÉ-PROCESSAMENTO PARA IDENTIFICAÇÃO DE DENTES SEROTINOS COM CISTOS                 |              2021 | BIBLIOGRÁFICA      | TRABALHO EM ANAIS     | nan       | nan           | nan      |               0    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||ANÁLISE DE TOPOLOGIAS EM TRAÇADOR DE CURVA I-V APLICADOS EM MÓDULOS FOTOVOLTAICOS||BIBLIOGRÁFICA||LIVRO                                                                       | ANÁLISE DE TOPOLOGIAS EM TRAÇADOR DE CURVA I-V APLICADOS EM MÓDULOS FOTOVOLTAICOS                                                         |              2021 | BIBLIOGRÁFICA      | LIVRO                 | nan       |   9.78659e+12 | nan      |               0    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||ANÁLISE DO CURSO DE ENGENHARIA ELÉTRICA DO CAMPUS DE SOBRAL: PROMOVER O INTERESSE DE ESTUDANTES DO ENSINO MÉDIO E O CONTROLE DA EVASÃO||BIBLIOGRÁFICA||LIVRO                  | ANÁLISE DO CURSO DE ENGENHARIA ELÉTRICA DO CAMPUS DE SOBRAL: PROMOVER O INTERESSE DE ESTUDANTES DO ENSINO MÉDIO E O CONTROLE DA EVASÃO    |              2021 | BIBLIOGRÁFICA      | LIVRO                 | nan       |   9.78659e+12 | nan      |               0    |                    2 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||BACKSCATTER COOPERATION IN NOMA COMMUNICATIONS SYSTEMS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                                                    | BACKSCATTER COOPERATION IN NOMA COMMUNICATIONS SYSTEMS                                                                                    |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 1536-1276 | nan           | A1       |               1    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||BEHAVIOR ANALYSIS OF PV MODULES SUBJECTED TO HIGH-FREQUENCY CURRENT RIPPLES||BIBLIOGRÁFICA||TRABALHO EM ANAIS                                                                 | BEHAVIOR ANALYSIS OF PV MODULES SUBJECTED TO HIGH-FREQUENCY CURRENT RIPPLES                                                               |              2021 | BIBLIOGRÁFICA      | TRABALHO EM ANAIS     | nan       | nan           | nan      |               0    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||BLIND SOURCE SEPARATION IN PERSISTENT ATRIAL FIBRILLATION ELECTROCARDIOGRAMS USING BLOCK-TERM TENSOR DECOMPOSITION WITH LWNER CONSTRAINTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO | BLIND SOURCE SEPARATION IN PERSISTENT ATRIAL FIBRILLATION ELECTROCARDIOGRAMS USING BLOCK-TERM TENSOR DECOMPOSITION WITH LWNER CONSTRAINTS |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 2168-2208 | nan           | A1       |               1    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||BLOCKCHAIN-BASED WHISTLEBLOWING SERVICE TO SOLVE THE PROBLEM OF JOURNALISTIC CONFLICT OF INTEREST||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                         | BLOCKCHAIN-BASED WHISTLEBLOWING SERVICE TO SOLVE THE PROBLEM OF JOURNALISTIC CONFLICT OF INTEREST                                         |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 0003-4347 | nan           | A3       |               0.75 |                    2 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||CASE STUDY: VARIABLE-VOLTAGE DC BUS WITH ENERGY RECOVERY SYSTEM FOR INDUSTRIAL PLANTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                     | CASE STUDY: VARIABLE-VOLTAGE DC BUS WITH ENERGY RECOVERY SYSTEM FOR INDUSTRIAL PLANTS                                                     |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 2169-3536 | nan           | A3       |               0.75 |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||CELL-FREE MASSIVE MIMO-NOMA SYSTEMS WITH IMPERFECT SIC AND NON-RECIPROCAL CHANNELS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                        | CELL-FREE MASSIVE MIMO-NOMA SYSTEMS WITH IMPERFECT SIC AND NON-RECIPROCAL CHANNELS                                                        |              2021 | BIBLIOGRÁFICA      | ARTIGO EM PERIÓDICO   | 2162-2337 | nan           | A1       |               1    |                    1 | 2021_coleta.xlsx |          2021 |
| 22001018081P2||2021||CONVERSOR DE ALTO GANHO COM BAIXA ONDULAÇÃO DE CORRENTE DE ENTRADA E DE SAÍDA PARA APLICAÇÕES EM SISTEMAS FOTOVOLTAICOS||BIBLIOGRÁFICA||TRABALHO EM ANAIS                     | CONVERSOR DE ALTO GANHO COM BAIXA ONDULAÇÃO DE CORRENTE DE ENTRADA E DE SAÍDA PARA APLICAÇÕES EM SISTEMAS FOTOVOLTAICOS                   |              2021 | BIBLIOGRÁFICA      | TRABALHO EM ANAIS     | nan       | nan           | nan      |               0    |                    1 | 2021_coleta.xlsx |          2021 |

### 6.3 Exemplo do pivot de detalhamentos

| id_producao                                                                                                                                                                                    |   (PTT) Abragência Territorial |   (PTT) Abrangência Territorial |   (PTT) Anexo |   (PTT) Complexidade |   (PTT) Correspondência com os novos subtipos-produtos técnicos/tecnológicos |   (PTT) Código do Registro |   (PTT) Código do registro |   (PTT) Declaração de vínculo do produto com PDI da Instituição |   (PTT) Descrição do tipo de Impacto |   (PTT) Estágio da Tecnologia |   (PTT) Finalidade |   (PTT) Houve fomento? |   (PTT) Há registro/depósito de propriedade intelectual? |   (PTT) Há transferência de tecnologia/conhecimento? |   (PTT) Impacto - Demanda |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------:|--------------------------------:|--------------:|---------------------:|-----------------------------------------------------------------------------:|---------------------------:|---------------------------:|----------------------------------------------------------------:|-------------------------------------:|------------------------------:|-------------------:|-----------------------:|---------------------------------------------------------:|-----------------------------------------------------:|--------------------------:|
| 22001018081P2||2021||A FRAMEWORK FOR RADIO RESOURCE ALLOCATION AND SDMA GROUPING IN MASSIVE MIMO SYSTEMS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                   |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||A SEMI-DISTRIBUTED APPROACH FOR UPLINK MAX-MIN ENERGY EF-CIENCY OPTIMIZATION WITH MINIMUM USER SATISFACTION AND ADJACENCY CONSTRAINTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||AERIAL RECONFIGURABLE INTELLIGENT SURFACE-AIDED WIRELESS COMMUNICATION SYSTEMS||BIBLIOGRÁFICA||TRABALHO EM ANAIS                                                          |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||ANALYSIS OF ASYMMETRIC DUAL-HOP ENERGY HARVESTING-BASED WIRELESS COMMUNICATION SYSTEMS IN MIXED FADING ENVIRONMENTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                   |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||ANÁLISE COMPARATIVA DA INFLUÊNCIA DE OTIMIZADORES NO DESEMPENHO DE UMA CNN PARA DETECÇÃO DO CÂNCER DE MAMA||BIBLIOGRÁFICA||TRABALHO EM ANAIS                              |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||ANÁLISE DE REDES NEURAIS CONVOLUCIONAIS E TÉCNICAS DE PRÉ-PROCESSAMENTO PARA IDENTIFICAÇÃO DE DENTES SEROTINOS COM CISTOS||BIBLIOGRÁFICA||TRABALHO EM ANAIS               |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||ANÁLISE DE TOPOLOGIAS EM TRAÇADOR DE CURVA I-V APLICADOS EM MÓDULOS FOTOVOLTAICOS||BIBLIOGRÁFICA||LIVRO                                                                   |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||ANÁLISE DO CURSO DE ENGENHARIA ELÉTRICA DO CAMPUS DE SOBRAL: PROMOVER O INTERESSE DE ESTUDANTES DO ENSINO MÉDIO E O CONTROLE DA EVASÃO||BIBLIOGRÁFICA||LIVRO              |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||BACKSCATTER COOPERATION IN NOMA COMMUNICATIONS SYSTEMS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                                                |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |
| 22001018081P2||2021||BEHAVIOR ANALYSIS OF PV MODULES SUBJECTED TO HIGH-FREQUENCY CURRENT RIPPLES||BIBLIOGRÁFICA||TRABALHO EM ANAIS                                                             |                            nan |                             nan |           nan |                  nan |                                                                          nan |                        nan |                        nan |                                                             nan |                                  nan |                           nan |                nan |                    nan |                                                      nan |                                                  nan |                       nan |

### 6.4 Diagnóstico de granularidade

| id_producao                                                                                                                                                                                         | Título da Produção                                                                                                                           |   Ano da Produção |   n_autores |   n_docentes_autores |   n_detalhamentos |   n_tipos_detalhe |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------|------------------:|------------:|---------------------:|------------------:|------------------:|
| 22001018081P2||2023||A EXPERIÊNCIA DO PET-UFC NA AMBIENTAÇÃO DE ALUNOS INGRESSOS NO CURSO DE ENGENHARIA ELÉTRICA DA UNIVERSIDADE FEDERAL DO CEARÁ ? CAMPUS SOBRAL||BIBLIOGRÁFICA||LIVRO             | A EXPERIÊNCIA DO PET-UFC NA AMBIENTAÇÃO DE ALUNOS INGRESSOS NO CURSO DE ENGENHARIA ELÉTRICA DA UNIVERSIDADE FEDERAL DO CEARÁ ? CAMPUS SOBRAL |              2023 |           9 |                    1 |                37 |                37 |
| 22001018081P2||2021||METHODS, RADIO NETWORK NODE AND NETWORK NODE FOR HANDLING COMMUNICATION||TÉCNICA||PATENTE                                                                                      | METHODS, RADIO NETWORK NODE AND NETWORK NODE FOR HANDLING COMMUNICATION                                                                      |              2021 |           8 |                    1 |                32 |                32 |
| 22001018081P2||2021||IRS-ASSISTED MASSIVE MIMO-NOMA NETWORKS WITH POLARIZATION DIVERSITY||BIBLIOGRÁFICA||TRABALHO EM ANAIS                                                                          | IRS-ASSISTED MASSIVE MIMO-NOMA NETWORKS WITH POLARIZATION DIVERSITY                                                                          |              2021 |           8 |                    2 |                16 |                16 |
| 22001018081P2||2023||SYSTEM LEVEL EVALUATION OF NETWORK-CONTROLLED REPEATERS: PERFORMANCE IMPROVEMENT OF SERVING CELL AND INTERFERENCE IMPACT ON NEIGHBOR CELLS||BIBLIOGRÁFICA||TRABALHO EM ANAIS   | SYSTEM LEVEL EVALUATION OF NETWORK-CONTROLLED REPEATERS: PERFORMANCE IMPROVEMENT OF SERVING CELL AND INTERFERENCE IMPACT ON NEIGHBOR CELLS   |              2023 |           8 |                    1 |                16 |                16 |
| 22001018081P2||2021||TENSOR-BASED LEARNING FRAMEWORK FOR AUTOMATIC MULTICHANNEL VOLCANO-SEISMIC CLASSIFICATION||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                  | TENSOR-BASED LEARNING FRAMEWORK FOR AUTOMATIC MULTICHANNEL VOLCANO-SEISMIC CLASSIFICATION                                                    |              2021 |           8 |                    1 |                15 |                15 |
| 22001018081P2||2022||ADAPTABLE TDD SCHEME FOR MOBILE IAB CELLS||TÉCNICA||PATENTE                                                                                                                    | ADAPTABLE TDD SCHEME FOR MOBILE IAB CELLS                                                                                                    |              2022 |           7 |                    1 |                32 |                32 |
| 22001018081P2||2022||INTERFERENCE HANDLING IN MOBILE IAB CELLS||TÉCNICA||PATENTE                                                                                                                    | INTERFERENCE HANDLING IN MOBILE IAB CELLS                                                                                                    |              2022 |           7 |                    1 |                32 |                32 |
| 22001018081P2||2021||ANALYSIS OF ASYMMETRIC DUAL-HOP ENERGY HARVESTING-BASED WIRELESS COMMUNICATION SYSTEMS IN MIXED FADING ENVIRONMENTS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                        | ANALYSIS OF ASYMMETRIC DUAL-HOP ENERGY HARVESTING-BASED WIRELESS COMMUNICATION SYSTEMS IN MIXED FADING ENVIRONMENTS                          |              2021 |           7 |                    1 |                15 |                15 |
| 22001018081P2||2021||CELL-FREE MASSIVE MIMO-NOMA SYSTEMS WITH IMPERFECT SIC AND NON-RECIPROCAL CHANNELS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                         | CELL-FREE MASSIVE MIMO-NOMA SYSTEMS WITH IMPERFECT SIC AND NON-RECIPROCAL CHANNELS                                                           |              2021 |           7 |                    1 |                15 |                15 |
| 22001018081P2||2021||IRS-ASSISTED MASSIVE MIMO-NOMA NETWORKS: EXPLOITING WAVE POLARIZATION||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                                      | IRS-ASSISTED MASSIVE MIMO-NOMA NETWORKS: EXPLOITING WAVE POLARIZATION                                                                        |              2021 |           7 |                    2 |                15 |                15 |
| 22001018081P2||2021||NON-ISOLATED HIGH STEP-UP DC-DC CONVERTER BASED ON COUPLED INDUCTORS, DIODE-CAPACITOR NETWORKS, AND VOLTAGE MULTIPLIER CELLS||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO               | NON-ISOLATED HIGH STEP-UP DC-DC CONVERTER BASED ON COUPLED INDUCTORS, DIODE-CAPACITOR NETWORKS, AND VOLTAGE MULTIPLIER CELLS                 |              2021 |           7 |                    2 |                15 |                15 |
| 22001018081P2||2022||ANALYSIS OF THE INFLUENCE OF PRE-PROCESSING TECHNIQUES WITH CONVOLUTIONAL NEURAL NETWORKS FOR AUTOMATIC DETECTION OF CYSTS IN WISDOM TEETH||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO | ANALYSIS OF THE INFLUENCE OF PRE-PROCESSING TECHNIQUES WITH CONVOLUTIONAL NEURAL NETWORKS FOR AUTOMATIC DETECTION OF CYSTS IN WISDOM TEETH   |              2022 |           7 |                    1 |                15 |                15 |
| 22001018081P2||2022||PAVING THE WAY TOWARDS MOBILE IAB: PROBLEMS, SOLUTIONS AND CHALLENGES||BIBLIOGRÁFICA||ARTIGO EM PERIÓDICO                                                                      | PAVING THE WAY TOWARDS MOBILE IAB: PROBLEMS, SOLUTIONS AND CHALLENGES                                                                        |              2022 |           7 |                    1 |                15 |                15 |
| 22001018081P2||2021||ESTUDO DO SISTEMA DE CONVERSÃO DE ENERGIA FOTOVOLTAICA DE ÚNICO ESTÁGIO COM CONEXÃO DIRETA AO SISTEMA ELÉTRICO TRIFÁSICO||BIBLIOGRÁFICA||LIVRO                                 | ESTUDO DO SISTEMA DE CONVERSÃO DE ENERGIA FOTOVOLTAICA DE ÚNICO ESTÁGIO COM CONEXÃO DIRETA AO SISTEMA ELÉTRICO TRIFÁSICO                     |              2021 |           6 |                    1 |                37 |                37 |
| 22001018081P2||2021||SISTEMA DE GERAÇÃO DE ENERGIA EÓLICA COM FILTRO ATIVO PARALELO A PARTIR DO GERADOR SÍNCRONO DE IMÃ PERMANENTE CONECTADO À REDE ELÉTRICA||BIBLIOGRÁFICA||LIVRO                  | SISTEMA DE GERAÇÃO DE ENERGIA EÓLICA COM FILTRO ATIVO PARALELO A PARTIR DO GERADOR SÍNCRONO DE IMÃ PERMANENTE CONECTADO À REDE ELÉTRICA      |              2021 |           6 |                    2 |                37 |                37 |

### 6.5 Log de carga

| arquivo_origem   |   ano_arquivo | aba_producao_origem    |   n_linhas |   n_colunas |
|:-----------------|--------------:|:-----------------------|-----------:|------------:|
| 2021_coleta.xlsx |          2021 | Produção Intelectual   |       1801 |          24 |
| 2022_coleta.xlsx |          2022 | Produção Intelectual   |        780 |          24 |
| 2023_coleta.xlsx |          2023 | Produção Intelectual   |        967 |          24 |
| 2024_coleta.xlsx |          2024 | Produções Intelectuais |        873 |          21 |

## 7. Saídas consolidadas do pipeline

### 7.1 Docentes (consolidado)

| Nome do Autor                       |   n_producoes |   pontuacao_total |   pr_docente |   A1 |   A2 |   A3 |   A4 |   B1 |   B3 |   B4 |   SEM_QUALIS |   B2 |   dpi_docente_normalizado |
|:------------------------------------|--------------:|------------------:|-------------:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|-------------:|-----:|--------------------------:|
| DANIEL BENEVIDES DA COSTA           |            24 |            11.35  |       10.85  |   10 |    0 |    1 |    1 |    0 |    0 |    0 |           12 |    0 |                0.597368   |
| FRANCISCO RAFAEL MARQUES LIMA       |            30 |             6.85  |        6.35  |    4 |    0 |    3 |    1 |    0 |    0 |    0 |           22 |    0 |                0.360526   |
| CARLOS ALEXANDRE ROLIM FERNANDES    |            19 |             6.375 |        6.375 |    4 |    1 |    0 |    2 |    1 |    0 |    0 |           11 |    0 |                0.335526   |
| JOSE CLAUDIO DO NASCIMENTO          |             8 |             5.225 |        4.85  |    0 |    1 |    5 |    1 |    0 |    0 |    0 |            1 |    0 |                0.275      |
| JARBAS JOACI DE MESQUITA SA JUNIOR  |             4 |             2.475 |        2.475 |    1 |    1 |    0 |    1 |    0 |    0 |    0 |            1 |    0 |                0.130263   |
| EDILSON MINEIRO SA JUNIOR           |            23 |             1.5   |        1.125 |    0 |    0 |    2 |    0 |    0 |    0 |    0 |           21 |    0 |                0.0789474  |
| IALIS CAVALCANTE DE PAULA JUNIOR    |             9 |             1.2   |        1.2   |    0 |    0 |    0 |    2 |    0 |    0 |    0 |            7 |    0 |                0.0631579  |
| VANDILBERTO PEREIRA PINTO           |            12 |             0.85  |        0.85  |    0 |    0 |    1 |    0 |    0 |    1 |    0 |           10 |    0 |                0.0447368  |
| ANTONIO EMERSON BARROS TOMAZ        |             9 |             0.75  |        0.375 |    0 |    0 |    1 |    0 |    0 |    0 |    0 |            8 |    0 |                0.0394737  |
| KLEBER CESAR ALVES DE SOUZA         |             4 |             0.75  |        0.375 |    0 |    0 |    1 |    0 |    0 |    0 |    0 |            3 |    0 |                0.0394737  |
| FISCHER JONATAS FERREIRA            |            11 |             0.75  |        0.75  |    0 |    0 |    1 |    0 |    0 |    0 |    0 |           10 |    0 |                0.0394737  |
| ISAAC ROCHA MACHADO                 |             5 |             0.75  |        0.75  |    0 |    0 |    1 |    0 |    0 |    0 |    0 |            4 |    0 |                0.0394737  |
| ADSON BEZERRA MOREIRA               |            19 |             0.05  |        0.025 |    0 |    0 |    0 |    0 |    0 |    0 |    1 |           18 |    0 |                0.00263158 |
| VANESSA SIQUEIRA DE CASTRO TEIXEIRA |             9 |             0.05  |        0.025 |    0 |    0 |    0 |    0 |    0 |    0 |    1 |            8 |    0 |                0.00263158 |
| ICARO BEZERRA VIANA                 |             3 |             0     |        0     |    0 |    0 |    0 |    0 |    0 |    0 |    0 |            3 |    0 |                0          |
| MARCIO ANDRE BAIMA AMORA            |            12 |             0     |        0     |    0 |    0 |    0 |    0 |    0 |    0 |    0 |           12 |    0 |                0          |
| MARCELO MARQUES SIMOES DE SOUZA     |             7 |             0     |        0     |    0 |    0 |    0 |    0 |    0 |    0 |    0 |            7 |    0 |                0          |
| MARCUS ROGERIO DE CASTRO            |             2 |             0     |        0     |    0 |    0 |    0 |    0 |    0 |    0 |    0 |            2 |    0 |                0          |
| WENDLEY SOUZA DA SILVA              |             2 |             0     |        0     |    0 |    0 |    0 |    0 |    0 |    0 |    0 |            2 |    0 |                0          |

![Ranking DPI](grafico_ranking_dpi.png)

![Ranking PR](grafico_ranking_pr.png)

### 7.2 Programa (consolidado)

|   DP |   n_docentes_com_producao |   n_producoes_com_autoria_docente |   pontuacao_total_programa |   DPI_programa |   PR_programa |
|-----:|--------------------------:|----------------------------------:|---------------------------:|---------------:|--------------:|
|   19 |                        19 |                               183 |                     38.925 |         1.9145 |        36.375 |

### 7.3 Docentes por ano

| Nome do Autor                       |   n_producoes |   pontuacao_total |   pr_docente |   A1 |   A3 |   A4 |   B4 |   SEM_QUALIS |   A2 |   B1 |   B2 |   B3 |   dpi_docente_normalizado |   Ano da Produção |
|:------------------------------------|--------------:|------------------:|-------------:|-----:|-----:|-----:|-----:|-------------:|-----:|-----:|-----:|-----:|--------------------------:|------------------:|
| DANIEL BENEVIDES DA COSTA           |            24 |            11.35  |       10.85  |   10 |    1 |    1 |    0 |           12 |    0 |    0 |    0 |    0 |                0.810714   |              2021 |
| FRANCISCO RAFAEL MARQUES LIMA       |            12 |             4.85  |        4.35  |    2 |    3 |    1 |    0 |            6 |    0 |    0 |    0 |    0 |                0.346429   |              2021 |
| CARLOS ALEXANDRE ROLIM FERNANDES    |             7 |             3     |        3     |    3 |    0 |    0 |    0 |            4 |    0 |    0 |    0 |    0 |                0.214286   |              2021 |
| EDILSON MINEIRO SA JUNIOR           |             7 |             1.5   |        1.125 |    0 |    2 |    0 |    0 |            5 |    0 |    0 |    0 |    0 |                0.107143   |              2021 |
| JOSE CLAUDIO DO NASCIMENTO          |             2 |             1.5   |        1.125 |    0 |    2 |    0 |    0 |            0 |    0 |    0 |    0 |    0 |                0.107143   |              2021 |
| ANTONIO EMERSON BARROS TOMAZ        |             2 |             0.75  |        0.375 |    0 |    1 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0.0535714  |              2021 |
| KLEBER CESAR ALVES DE SOUZA         |             3 |             0.75  |        0.375 |    0 |    1 |    0 |    0 |            2 |    0 |    0 |    0 |    0 |                0.0535714  |              2021 |
| ISAAC ROCHA MACHADO                 |             2 |             0.75  |        0.75  |    0 |    1 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0.0535714  |              2021 |
| ADSON BEZERRA MOREIRA               |             6 |             0.05  |        0.025 |    0 |    0 |    0 |    1 |            5 |    0 |    0 |    0 |    0 |                0.00357143 |              2021 |
| VANESSA SIQUEIRA DE CASTRO TEIXEIRA |             3 |             0.05  |        0.025 |    0 |    0 |    0 |    1 |            2 |    0 |    0 |    0 |    0 |                0.00357143 |              2021 |
| IALIS CAVALCANTE DE PAULA JUNIOR    |             2 |             0     |        0     |    0 |    0 |    0 |    0 |            2 |    0 |    0 |    0 |    0 |                0          |              2021 |
| MARCIO ANDRE BAIMA AMORA            |             4 |             0     |        0     |    0 |    0 |    0 |    0 |            4 |    0 |    0 |    0 |    0 |                0          |              2021 |
| MARCUS ROGERIO DE CASTRO            |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2021 |
| VANDILBERTO PEREIRA PINTO           |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2021 |
| FRANCISCO RAFAEL MARQUES LIMA       |             9 |             2     |        2     |    2 |    0 |    0 |    0 |            7 |    0 |    0 |    0 |    0 |                0.142857   |              2022 |
| JOSE CLAUDIO DO NASCIMENTO          |             2 |             1.625 |        1.625 |    0 |    1 |    0 |    0 |            0 |    1 |    0 |    0 |    0 |                0.116071   |              2022 |
| CARLOS ALEXANDRE ROLIM FERNANDES    |             2 |             1.6   |        1.6   |    1 |    0 |    1 |    0 |            0 |    0 |    0 |    0 |    0 |                0.114286   |              2022 |
| JARBAS JOACI DE MESQUITA SA JUNIOR  |             1 |             1     |        1     |    1 |    0 |    0 |    0 |            0 |    0 |    0 |    0 |    0 |                0.0714286  |              2022 |
| IALIS CAVALCANTE DE PAULA JUNIOR    |             1 |             0.6   |        0.6   |    0 |    0 |    1 |    0 |            0 |    0 |    0 |    0 |    0 |                0.0428571  |              2022 |
| ANTONIO EMERSON BARROS TOMAZ        |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2022 |
| FISCHER JONATAS FERREIRA            |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2022 |
| EDILSON MINEIRO SA JUNIOR           |             2 |             0     |        0     |    0 |    0 |    0 |    0 |            2 |    0 |    0 |    0 |    0 |                0          |              2022 |
| ADSON BEZERRA MOREIRA               |             6 |             0     |        0     |    0 |    0 |    0 |    0 |            6 |    0 |    0 |    0 |    0 |                0          |              2022 |
| ISAAC ROCHA MACHADO                 |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2022 |
| MARCIO ANDRE BAIMA AMORA            |             4 |             0     |        0     |    0 |    0 |    0 |    0 |            4 |    0 |    0 |    0 |    0 |                0          |              2022 |
| MARCUS ROGERIO DE CASTRO            |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2022 |
| VANDILBERTO PEREIRA PINTO           |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2022 |
| VANESSA SIQUEIRA DE CASTRO TEIXEIRA |             2 |             0     |        0     |    0 |    0 |    0 |    0 |            2 |    0 |    0 |    0 |    0 |                0          |              2022 |
| CARLOS ALEXANDRE ROLIM FERNANDES    |             6 |             1.775 |        1.775 |    0 |    0 |    1 |    0 |            3 |    1 |    1 |    0 |    0 |                0.118333   |              2023 |
| FISCHER JONATAS FERREIRA            |             4 |             0.75  |        0.75  |    0 |    1 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0.05       |              2023 |
| JOSE CLAUDIO DO NASCIMENTO          |             1 |             0.75  |        0.75  |    0 |    1 |    0 |    0 |            0 |    0 |    0 |    0 |    0 |                0.05       |              2023 |
| JARBAS JOACI DE MESQUITA SA JUNIOR  |             1 |             0.6   |        0.6   |    0 |    0 |    1 |    0 |            0 |    0 |    0 |    0 |    0 |                0.04       |              2023 |
| IALIS CAVALCANTE DE PAULA JUNIOR    |             4 |             0.6   |        0.6   |    0 |    0 |    1 |    0 |            3 |    0 |    0 |    0 |    0 |                0.04       |              2023 |
| ANTONIO EMERSON BARROS TOMAZ        |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2023 |
| ADSON BEZERRA MOREIRA               |             6 |             0     |        0     |    0 |    0 |    0 |    0 |            6 |    0 |    0 |    0 |    0 |                0          |              2023 |
| FRANCISCO RAFAEL MARQUES LIMA       |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2023 |
| EDILSON MINEIRO SA JUNIOR           |            13 |             0     |        0     |    0 |    0 |    0 |    0 |           13 |    0 |    0 |    0 |    0 |                0          |              2023 |
| ICARO BEZERRA VIANA                 |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2023 |
| KLEBER CESAR ALVES DE SOUZA         |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2023 |
| MARCELO MARQUES SIMOES DE SOUZA     |             4 |             0     |        0     |    0 |    0 |    0 |    0 |            4 |    0 |    0 |    0 |    0 |                0          |              2023 |
| MARCIO ANDRE BAIMA AMORA            |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2023 |
| VANDILBERTO PEREIRA PINTO           |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2023 |
| VANESSA SIQUEIRA DE CASTRO TEIXEIRA |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2023 |
| JOSE CLAUDIO DO NASCIMENTO          |             3 |             1.35  |        1.35  |    0 |    1 |    1 |    0 |            1 |    0 |    0 |    0 |    0 |                0.0964286  |              2024 |
| JARBAS JOACI DE MESQUITA SA JUNIOR  |             2 |             0.875 |        0.875 |    0 |    0 |    0 |    0 |            1 |    1 |    0 |    0 |    0 |                0.0625     |              2024 |
| VANDILBERTO PEREIRA PINTO           |             3 |             0.85  |        0.85  |    0 |    1 |    0 |    0 |            1 |    0 |    0 |    0 |    1 |                0.0607143  |              2024 |
| CARLOS ALEXANDRE ROLIM FERNANDES    |             4 |             0     |        0     |    0 |    0 |    0 |    0 |            4 |    0 |    0 |    0 |    0 |                0          |              2024 |
| ADSON BEZERRA MOREIRA               |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2024 |
| ANTONIO EMERSON BARROS TOMAZ        |             5 |             0     |        0     |    0 |    0 |    0 |    0 |            5 |    0 |    0 |    0 |    0 |                0          |              2024 |
| FRANCISCO RAFAEL MARQUES LIMA       |             8 |             0     |        0     |    0 |    0 |    0 |    0 |            8 |    0 |    0 |    0 |    0 |                0          |              2024 |
| FISCHER JONATAS FERREIRA            |             6 |             0     |        0     |    0 |    0 |    0 |    0 |            6 |    0 |    0 |    0 |    0 |                0          |              2024 |
| EDILSON MINEIRO SA JUNIOR           |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2024 |
| IALIS CAVALCANTE DE PAULA JUNIOR    |             2 |             0     |        0     |    0 |    0 |    0 |    0 |            2 |    0 |    0 |    0 |    0 |                0          |              2024 |
| MARCELO MARQUES SIMOES DE SOUZA     |             3 |             0     |        0     |    0 |    0 |    0 |    0 |            3 |    0 |    0 |    0 |    0 |                0          |              2024 |
| MARCIO ANDRE BAIMA AMORA            |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2024 |
| VANESSA SIQUEIRA DE CASTRO TEIXEIRA |             1 |             0     |        0     |    0 |    0 |    0 |    0 |            1 |    0 |    0 |    0 |    0 |                0          |              2024 |
| WENDLEY SOUZA DA SILVA              |             2 |             0     |        0     |    0 |    0 |    0 |    0 |            2 |    0 |    0 |    0 |    0 |                0          |              2024 |

### 7.4 Programa por ano

|   DP |   n_docentes_com_producao |   n_producoes_com_autoria_docente |   pontuacao_total_programa |   DPI_programa |   PR_programa |   Ano da Produção |
|-----:|--------------------------:|----------------------------------:|---------------------------:|---------------:|--------------:|------------------:|
|   14 |                        14 |                                68 |                     24.55  |         1.5714 |        22     |              2021 |
|   14 |                        14 |                                34 |                      6.825 |         0.4875 |         6.825 |              2022 |
|   15 |                        15 |                                42 |                      4.475 |         0.2983 |         4.475 |              2023 |
|   14 |                        14 |                                39 |                      3.075 |         0.2196 |         3.075 |              2024 |

![DPI do programa por ano](grafico_dpi_programa_ano.png)

![PR do programa por ano](grafico_pr_programa_ano.png)

# Projetos
Projetos práticos com base em minhas experiências profissionais


# Análise de Serviços Operacionais em Equipamentos Elétricos

Este projeto tem como objetivo analisar dados simulados de serviços operacionais aplicados a equipamentos elétricos, com base em experiências reais vivenciadas na área de Pré-Operação de uma distribuidora de energia.

## Objetivos

- Analisar a distribuição e variação do tempo de execução por tipo de serviço.
- Avaliar o impacto da criticidade dos serviços na eficiência operacional.
- Relacionar o tipo de equipamento ao tipo de serviço mais frequente.
- Comparar serviços programados com os efetivamente executados ao longo do tempo.

## Tecnologias Utilizadas

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Dataset simulado em CSV

## Estrutura dos Arquivos

- `base_servicos_pre_operacao.csv`: base de dados simulada com 200 registros.
- `Análise Equipamentos e Operação.ipynb`: notebook com todo o processo de análise e visualização de dados.
- Imagens dos principais gráficos (salvas automaticamente pelo notebook).

## Descrição da Base de Dados

A base de dados simula registros de serviços aplicados a equipamentos da rede elétrica, com as seguintes colunas:

| Coluna                 | Descrição |
|------------------------|------------------------------------------------------|
| ID_Equipamento         | Identificador do equipamento |
| Tipo_Equipamento       | Tipo do equipamento (Transformador, Disjuntor etc.) |
| Regiao                 | Local onde o serviço foi realizado |
| Tipo_Servico           | Natureza do serviço (Inspeção, Manutenção etc.) |
| Critico                | Indicador de criticidade (Sim/Não) |
| Status_Servico         | Status atual do serviço (Concluído, Pendente etc.) |
| Data_Programada        | Data prevista para execução |
| Data_Execucao          | Data real de execução |
| Tempo_Execucao_min     | Duração da execução em minutos |

##  Principais Resultados

- **Serviços críticos** tendem a ser executados mais rapidamente e com menor variação de tempo.
- **Inspeções** apresentaram a maior dispersão de tempo entre os tipos de serviço.
- **Religadores** foram os equipamentos mais frequentemente inspecionados.
- Identificou-se um descompasso entre serviços programados e executados em determinadas datas, o que pode indicar gargalos operacionais.

## ⚠ Observação

Os dados utilizados neste projeto foram **gerados artificialmente** e não representam informações reais.O objetivo é exclusivamente demonstrativo.

## 📎 Autor

Paulo Ricardo Monteiro Martins  

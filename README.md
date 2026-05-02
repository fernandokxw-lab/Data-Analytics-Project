# Projeto de Analytics: Banco Vitória (BanVic)

Este repositório contém a solução do desafio de Engenharia de Analytics/Análise de Dados para o Banco Vitória (BanVic). O objetivo foi transformar dados brutos em inteligência de negócio para apoiar a tomada de decisão estratégica da instituição.

##  Contexto do Projeto
O BanVic buscava amadurecer a sua cultura de dados para entender melhor o desempenho das suas agências, colaboradores e perfis de clientes. O projeto envolveu desde o tratamento de bases de dados complexas até a geração de recomendações estratégicas.

### Principais Objetivos:
* Analisar a distribuição geográfica e o perfil dos clientes.
* Monitorar transações e fluxos financeiros.
* Avaliar a eficiência de agências e colaboradores.
* Propor melhorias na política de crédito e retenção de clientes.

## Ferramentas e Metodologia
A metodologia seguiu o fluxo de ponta a ponta em BI:
1.  **Extração:** Carga de dados das bases do banco.
2.  **ETL (Power Query):** Limpeza de dados, padronização de tipos e criação de colunas condicionais.
3.  **Modelagem de Dados:** Criação de relacionamentos entre tabelas de clientes, transações, agências e colaboradores.
4.  **Análise Quantitativa (DAX):** Criação de medidas para KPIs (Taxa de aprovação, faturamento médio, volume de transações).
5.  **Design (Canva):** Planejamento estético e layout do dashboard para melhor experiência do usuário (UX).


## Visualização do Dashboard e algumas análises feitas

| Visão Geral do Dashboard |
| :---: |
| <img width="100%" src="https://github.com/user-attachments/assets/74d04f66-918c-4995-a5d3-3112110a87cf" /> |

| Ciclo ETL: Extração, Transformação e Carga |
| :---: |
| <img width="1917" height="985" alt="Captura de tela 2025-01-27 174651" src="https://github.com/user-attachments/assets/f1f1b018-2d2c-494e-bfdb-73068c4b419d" />|

| Modelagem de dados e análise quantitativa | 
| :---: |
| <img width="1726" height="680" alt="Captura de tela 2025-01-27 174528" src="https://github.com/user-attachments/assets/ca5c8c2a-6815-4010-89f4-fe09bdb8292a" />
 | <img width="1919" height="1015" alt="Captura de tela 2025-01-27 174925" src="https://github.com/user-attachments/assets/e097b523-bfdd-40f5-b205-28a51359df4d"/>|

| Fluxo Transacional | Clientes com maiores transações |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/7260b3b8-c71f-49e8-bbb6-698315269c8e" width="100%" /> | <img src="https://github.com/user-attachments/assets/4b13ae67-8a28-4adf-8322-b83289dc3c9d" width="100%" /> |

| Análise de tendências |
| :---: |
| <img src="https://github.com/user-attachments/assets/8b3e9836-8cbd-4835-a1c8-a343ae2e0d16" width="60%" /> |



## Insights e Resultados
* **Concentração de Mercado:** O Sudeste detém 47% da base de clientes, evidenciando uma oportunidade de expansão estratégica nas regiões Sul e Nordeste. A análise demográfica revelou que o BanVic possui uma base madura, concentrada no público 45+ anos. Este insight permite direcionar a comunicação de marketing para produtos de crédito e investimento mais sofisticados, que atendam a essa estabilidade financeira.
* **Eficiência Operacional:** Identificação da Agência 7 e do Colaborador 64 como benchmarks de alta performance.
* **Oportunidade de Crédito:** Constatação de que a taxa de aprovação atual é de apenas 25,7%. Proposta de revisão da política de crédito integrando indicadores macroeconômicos e de inadimplência.
* **Sazonalidade:** Identificação de picos transacionais que permitem ao banco planejar melhor as campanhas de marketing. Identificação de sazonalidade com picos entre julho e novembro, e picos no meio do mês, permitindo planejar a infraestrutura de atendimento e campanhas de vendas.

## 📁 Estrutura do Repositório
* `dados`: Dataset utilizado neste projeto
* `LH_EA_AD_FERNANDO_WANG.pdf`: Relatório final com a documentação completa da análise. 
* `LH_EA_AD_FERNANDO_WANG.pbix`: Arquivo fonte do Power BI.

---
**Desenvolvido por Fernando Wang**

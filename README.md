# Desafio_A3Data
Análise de uma base de dados com dados dos clientes e perfil de compra de uma empresa de telecomunicações. O objetivo deste teste é conseguir explorar e demonstrar habilidades técnicas e de negócio, trazendo insights acionáveis para o negócio.

**Definição do problema**
Objetivo: Reduzir o churn (taxa de cancelamento) dos clientes de uma empresa de telecomunicações.
Motivação: O custo elevado de setup (instalação) torna a retenção de clientes crucial para a sustentabilidade financeira da empresa.

**Roadmap**
1. Análise Exploratória de Dados (EDA)
Coleta e compreensão dos dados;
Limpeza e pré-processamento dos dados;
Análise descritiva dos dados.

2. Levantamento de Hipóteses
Identificação de possíveis fatores que contribuem para o churn.

3. Modelagem e Análise Preditiva
Construção de modelos preditivos para identificar clientes com maior probabilidade de churn.

4. Geração de Insights e Ações
Identificação de ações estratégicas para reduzir o churn;
Estimativa do impacto das ações sugeridas.

**Metodologia CRISP-DM (Cross Industry Standard Process for Data Mining)**
1. Compreensão do Negócio (Business Understanding)
2. Compreensão dos Dados (Data Understanding)
3. Preparação dos Dados (Data Preparation)
4. Modelagem (Modeling)
5. Avaliação (Evaluation)
6. Implementação (Deployment)

**Informação da base de dados**
Colunas: 
customerID (ID do Cliente) - Identificador único para cada cliente
gender (Gênero) - Gênero do cliente (Masculino, Feminino)
SeniorCitizen (Idoso) - Indica se o cliente é idoso (1 para sim, 0 para não)
Partner (Parceiro) - Indica se o cliente tem um parceiro (Sim, Não)
Dependents (Dependentes) - Indica se o cliente tem dependentes (Sim, Não)
tenure (Tempo de Permanência) - Número de meses que o cliente permaneceu com a empresa
PhoneService (Serviço de Telefone) - Indica se o cliente tem serviço de telefone (Sim, Não)
MultipleLines (Múltiplas Linhas) - Indica se o cliente tem múltiplas linhas (Sim, Não, Sem serviço de telefone)
InternetService (Serviço de Internet) - Tipo de serviço de internet do cliente (DSL, Fibra Óptica, Não)
OnlineSecurity (Segurança Online) - Indica se o cliente tem serviço de segurança online (Sim, Não, Sem serviço de internet)
OnlineBackup (Backup Online) - Indica se o cliente tem serviço de backup online (Sim, Não, Sem serviço de internet)
DeviceProtection (Proteção de Dispositivo) - Indica se o cliente tem serviço de proteção de dispositivo (Sim, Não, Sem serviço de internet)
TechSupport (Suporte Técnico) - Indica se o cliente tem suporte técnico (Sim, Não, Sem serviço de internet)
StreamingTV (Streaming de TV) - Indica se o cliente tem serviço de streaming de TV (Sim, Não, Sem serviço de internet)
StreamingMovies (Streaming de Filmes) - Indica se o cliente tem serviço de streaming de filmes (Sim, Não, Sem serviço de internet)
Contract (Contrato) - Tipo de contrato do cliente (Mensal, Anual, Bienal)
PaperlessBilling (Faturamento sem Papel) - Indica se o cliente optou por faturamento sem papel (Sim, Não)
PaymentMethod (Método de Pagamento) - Método de pagamento do cliente (Boleto Eletrônico, Cartão de Crédito, Cheque Eletrônico, Transferência Bancária)
MonthlyCharges (Cobrança Mensal) - Valor cobrado ao cliente mensalmente
TotalCharges (Cobrança Total) - Valor total cobrado ao cliente até o momento
Churn (Cancelamento) - Indica se o cliente cancelou o serviço (Sim, Não)

**Processamento e Limpeza dos Dados**
A base de dados dispõe de 7043 linhas, 21 colunas, 0 dados duplicados, 11 valores ausentes na coluna TotalCharges (Cobrança totais). Devido a baixa contagem de valores ausentes, optou-se pela exclusão dos mesmos.
Após a exclusão dos valores ausentes, a base de dados tratada dispõe de 7032 observações e 21 colunas.


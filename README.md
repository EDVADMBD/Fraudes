# Fraudes
O projeto de fraudes foi criado para detectar e prevenir transações suspeitas em tempo real, garantindo segurança e confiança para clientes e operações da empresa. 

<img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/f841cd45-1fbe-4e90-87ba-656835363600" />


📖 Storytelling do Projeto de Fraudes com CI/CD no GCP
Era uma vez uma equipe determinada a enfrentar um dos maiores desafios do mundo digital: fraudes em sistemas financeiros. Cada transação suspeita era como uma sombra que ameaçava a confiança dos clientes e a reputação da empresa.

🌱 O início
No começo, tudo era manual. Logs espalhados, scripts rodando em notebooks isolados, e uma sensação constante de que o inimigo estava sempre um passo à frente. A equipe sabia que precisava de algo maior: um pipeline automatizado, capaz de reagir rápido e com segurança.

⚙️ A virada tecnológica
Foi aí que surgiu a ideia de unir forças entre Databricks e Google Cloud Build.

O Databricks seria o cérebro: processando dados, treinando modelos de machine learning e aplicando regras inteligentes.

O Cloud Build seria o coração que bombeia o fluxo contínuo: garantindo que cada atualização de código, cada ajuste de modelo, fosse entregue com confiança e velocidade.

A chave para essa integração estava guardada em um cofre digital: a service account JSON, que permitia que o pipeline falasse a língua do Google Cloud com segurança.

🚀 A construção
O time desenhou o notebook:

Primeiro, gerar credenciais seguras a partir da chave.

Depois, montar o payload que acionaria o job no Databricks.

Por fim, disparar o build no Cloud Build, como quem acende uma tocha que ilumina o caminho da automação.

Cada etapa era validada com cuidado: tokens renovados, payloads revisados, erros tratados com resiliência. O projeto não era apenas código, era uma linha de defesa contra fraudes.

🛡️ O impacto
Com o pipeline rodando, a equipe ganhou:

Velocidade: novos modelos de detecção de fraude podiam ser implantados em minutos.

Segurança: credenciais protegidas, auditoria clara, conformidade com LGPD.

Confiança: clientes e gestores sabiam que o sistema estava sempre atualizado e vigilante.

🌟 O futuro.
Esse projeto não é apenas uma solução técnica. É uma história de como tecnologia e estratégia se unem para proteger pessoas. Cada linha de código é um tijolo na muralha contra fraudes. Cada build disparado é um lembrete de que a inovação pode ser a melhor arma contra ameaças invisíveis.

# TOPICOS

## 📓 Notebook

[![Abrir Notebook](https://img.shields.io/badge/A%20--%20Ingestão%20de%20Dados-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/01_data_ingestion.%20(1).ipynb)
[![B - Conexões e credenciais](https://img.shields.io/badge/B%20--%20Conexões%20e%20credenciais-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/02%20-%20Conex%C3%B5es_catalog.ipynb) [![C - Avaliação de Registros](https://img.shields.io/badge/C%20--%20Avaliação%20de%20Registros-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/04_evaluation_and_registry..ipynb) [![D - Monitoramento](https://img.shields.io/badge/D%20--%20Monitoramento-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/05_batch_scoring.ipynb) [![E - Dashboard Visual](https://img.shields.io/badge/E%20--%20Dashboard%20Visual-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/06_model_monitoring.py%20c.ipynb) [![F - Dashboard + Alertas](https://img.shields.io/badge/F%20--%20Dashboard%20+%20Alertas-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/06.1_model_monitoring.py.ipynb) [![G - Dashboard por Criticidade](https://img.shields.io/badge/G%20--%20Dashboard%20por%20Criticidade-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/07_model_retraining.py%2C.ipynb) [![H - CI/CD no GCP](https://img.shields.io/badge/H%20--%20CI/CD%20no%20GCP-Notebook-blue?style=for-the-badge)](https://github.com/EDVADMBD/Fraudes/blob/main/08_ci_cd_pipeline.py.ipynb)


# AREAS DE TRABALHO
# 01 - Databricks
https://github.com/EDVADMBD/Fraudes/blob/main/area_1.JPG

# 02 - Projeto GCP
https://github.com/EDVADMBD/Fraudes/blob/main/area_2.JPG

# 03 - Contas de serviços
https://github.com/EDVADMBD/Fraudes/blob/main/area_3.JPG



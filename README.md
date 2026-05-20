# santander-dev-week-etl
Santander Dev Week — Pipeline ETL com IA
Projeto desenvolvido durante a Santander Dev Week 2023 com foco no fluxo ETL (Extract, Transform, Load): leitura de dados de clientes em CSV, geração de mensagens personalizadas via IA (Claude API) e salvamento do resultado enriquecido.
O que é ETL?
Extract — lê o users.csv com nome, conta, cartão e saldo.
Transform — a IA gera uma mensagem financeira personalizada para cada cliente.
Load — salva tudo em users_com_mensagens.csv.
Como rodar

Instale as dependências: pip install -r requirements.txt
Adicione sua chave nos Secrets do Colab (ícone 🔑), com o nome ANTHROPIC_API_KEY
Execute o notebook SantanderDevWeekETL.ipynb célula por célula

Tecnologias
Python · pandas · Anthropic SDK · Google Colab

Desenvolvido por Caio Viana Nogueira Xavier

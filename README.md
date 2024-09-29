
# 🚀 Explorando IA Generativa em um Pipeline de ETL com Python

Este projeto utiliza um pipeline de ETL em Python para coletar dados de usuários de uma API externa, gerar conteúdo com IA e atualizar informações no banco de dados. O código também integra com a API da OpenAI para criar mensagens personalizadas para os usuários, explorando IA generativa aplicada ao marketing bancário.

## ✨ Funcionalidades

1. **Coleta de Dados**: Faz a leitura de um arquivo CSV (`SDW2023.csv`) para obter IDs de usuários.
2. **Chamada à API**: Consulta informações detalhadas dos usuários em uma API externa.
3. **Integração com OpenAI**: Utiliza o modelo GPT-3.5 para gerar conteúdo personalizado de marketing para cada usuário.
4. **Atualização de Dados**: Atualiza os dados dos usuários na API após a adição das mensagens geradas pela IA.

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem principal para execução do pipeline de ETL.
- **Pandas**: Manipulação de dados, leitura de arquivos CSV.
- **Requests**: Realiza chamadas HTTP para interagir com a API externa.
- **OpenAI API**: Gera mensagens personalizadas para usuários com GPT-3.5.

## 📁 Estrutura do Código

- **Leitura de CSV**: O arquivo `SDW2023.csv` é lido para extrair os IDs dos usuários.
- **Consulta de Usuários**: Para cada ID, as informações detalhadas do usuário são obtidas a partir de uma API RESTful.
- **Geração de Conteúdo com IA**: A IA cria uma mensagem de marketing personalizada para cada usuário, focando em investimentos.
- **Atualização na API**: O usuário é atualizado na API, incluindo a nova mensagem de marketing.

## 📋 Instruções de Uso

1. **Clone o repositório**:
   ```
   git clone https://github.com/marcos-xavier21/IA_Generativa.git
   ```
2. **Instale as dependências**:
   ```
   pip install pandas requests openai
   ```
3. **Configure sua chave de API do OpenAI**:
   No código, substitua a variável `openai_api_key` pela sua chave de API.

4. **Execute o script**:
   ```
   python etl_script.py
   ```

## 🚀 Próximos Passos

- Adicionar tratamento de erros e logging.
- Implementar suporte a múltiplos idiomas para as mensagens geradas pela IA.
- Melhorar a eficiência do pipeline com processamento paralelo.


---

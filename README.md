# Pipeline ETL com Python: Geração de Mensagens Personalizadas 🚀

Este projeto foi desenvolvido como parte de um desafio prático focado em Ciência de Dados e Engenharia de Dados. O objetivo foi criar um pipeline de **ETL (Extract, Transform, Load)** simplificado para processar dados de clientes e gerar recomendações personalizadas.

## 📋 Contexto do Desafio
O desafio consistia em simular um fluxo de trabalho onde dados de usuários são extraídos, passam por uma etapa de transformação (enriquecimento com lógica de negócio ou IA) e são carregados em um novo destino.

## 🛠️ Tecnologias Utilizadas
*   **Python**: Linguagem principal.
*   **Pandas**: Biblioteca para manipulação e análise de dados.
*   **Google Colab**: Ambiente de desenvolvimento em nuvem.

## ⚙️ O Pipeline de ETL

### 1. Extract (Extração)
Nesta etapa, os dados foram simulados através de um dicionário Python que foi convertido em um arquivo **CSV** (`clientes.csv`). O processo simula a leitura de dados brutos que poderiam vir de uma API ou banco de dados relacional.

### 2. Transform (Transformação)
Aqui reside a "inteligência" do projeto. Foi implementada uma lógica de negócio (simulando uma IA) que:
*   Analisa o saldo bancário de cada cliente.
*   Aplica uma regra condicional:
    *   **Saldo > 4000**: Sugere investimentos em Tesouro Direto.
    *   **Saldo <= 4000**: Incentiva a criação de uma reserva de emergência.
*   Cria uma nova coluna de dados enriquecida com essas mensagens personalizadas.

### 3. Load (Carregamento)
O conjunto de dados final, agora transformado e com valor agregado, é exportado para um novo arquivo chamado `clientes_com_mensagens.csv`, pronto para ser utilizado por outras equipes (como Marketing ou Vendas).

## 🚀 Como executar o projeto
1.  Abra o [Google Colab](https://colab.research.google.com/).
2.  Crie um novo notebook.
3.  Copie o código do arquivo `main.py` (ou as células do notebook deste repositório).
4.  Execute as células para ver os arquivos sendo gerados em tempo real.

---
Desenvolvido por Vitor Garcia como demonstração de estudos em Python e Engenharia de Dados.

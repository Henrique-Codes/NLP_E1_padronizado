# Processamento de Linguagem Natural — OIAA (Etapa 1) 📚

Este repositório contém a solução padronizada para o desafio de Processamento de Linguagem Natural (Etapa 1) da Olimpíada de IA Aplicada. O objetivo do modelo é prever e restaurar palavras omitidas (trechos com a marcação `<MASK>`) em textos históricos da língua portuguesa.

## 📁 Estrutura do Repositório

* `NLP_E1_padronizado.ipynb`: Notebook oficial do desafio estruturado rigidamente em 9 seções conforme o padrão da competição.
* `requirements.txt`: Lista de dependências e bibliotecas necessárias para a reprodução do fluxo.
* `README.md`: Instruções de instalação, configuração e execução.

## 🚀 Como Executar o Projeto

### Pré-requisitos
Recomenda-se a utilização de um ambiente com suporte a aceleração por GPU (como o Google Colab com T4 ou ambiente local com CUDA configurado) devido ao uso de arquiteturas de redes neurais profundas.

### Passo 1: Obter os arquivos do projeto
Baixe ou clone os arquivos deste repositório para o seu diretório local.

### Passo 2: Instalação das dependências
Abra o seu terminal na pasta raiz do projeto e instale as bibliotecas explícitas executando o comando:
```bash
pip install -r requirements.txt

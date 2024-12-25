# Augmented Analytics com Inteligência Artificial e LLMs

Este projeto utiliza técnicas de análise aumentada com Inteligência Artificial e Modelos de Linguagem de Grande Escala (LLMs) para fornecer respostas a perguntas baseadas em documentos PDF.

## Features

- Carregamento de documentos PDF
- Extração de texto e embeddings
- Armazenamento vetorial com ChromaDB
- Respostas a perguntas utilizando OpenAI GPT
- Interface web com Flask

## Requisitos

- Python 3.8+

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/tiluan/augmented-analytics-with-AI-and-LLMs.git
    cd augmented-analytics-with-AI-and-LLMs
    ```

2. Crie e ative um ambiente virtual:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure as variáveis de ambiente:
    Crie um arquivo [.env] na raiz do projeto e adicione suas chaves de API do OpenAI:
    ```env
    OPENAI_API_KEY=sua_chave_openai_api

    A chave pode ser obtida através do site [OpenAI](https://platform.openai.com/api-keys)
    ```

## Uso

1. Inicie o servidor Flask:
    ```bash
    flask run
    ```

2. Acesse a aplicação em seu navegador:
    ```
    http://127.0.0.1:5000
    ```

3. Carregue seus documentos PDF na pasta **files** e faça perguntas através da interface web.

## Versões dos Pacotes

- Flask 2.0.1
- openai 0.10.2
- langchain 0.0.1
- chromadb 0.3.21
- python-dotenv 0.19.0

## Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request
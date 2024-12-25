# Augmented Analytics com Inteligência Artificial e LLMs

Este projeto utiliza técnicas de análise aumentada com Inteligência Artificial e Modelos de Linguagem de Grande Escala (LLMs) para fornecer respostas a perguntas baseadas em documentos PDF.

## Features

- Carregamento de documentos PDF
- Extração de texto e embeddings
- Armazenamento vetorial com ChromaDB
- Respostas a perguntas utilizando OpenAI GPT
- Interface web com Flask

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/augmented-analytics-with-AI-and-LLMs.git
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
    Crie um arquivo [.env](http://_vscodecontentref_/0) na raiz do projeto e adicione suas chaves de API do OpenAI:
    ```env
    OPENAI_API_KEY=your_openai_api_key
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

3. Carregue seus documentos PDF na pasta [files](http://_vscodecontentref_/1) e faça perguntas através da interface web.

## Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo LICENSE para mais detalhes.
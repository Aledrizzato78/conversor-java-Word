# conversor-java-Word
# Java Project to Word Converter

Este script Python converte um projeto Java completo em um documento Word, facilitando a revisão e documentação do código-fonte.

## Funcionalidades

- Percorre recursivamente um diretório de projeto Java
- Processa arquivos .java, .xml, .properties, .gradle e .md
- Cria um documento Word estruturado com o conteúdo do projeto
- Formata o código-fonte para melhor legibilidade no documento Word

## Requisitos

- Python 3.6+
- python-docx

## Instalação

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/java-to-word-converter.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd java-to-word-converter
   ```

3. Instale as dependências:
   ```
   pip install python-docx
   ```

## Uso

1. Abra o arquivo `java_to_word_converter.py` e modifique as seguintes variáveis conforme necessário:
   - `root_dir`: O caminho para o diretório raiz do seu projeto Java
   - `output_path`: O caminho onde você deseja salvar o documento Word gerado

2. Execute o script:
   ```
   python java_to_word_converter.py
   ```

3. O script processará o projeto e criará um arquivo Word no local especificado.

## Personalização

Você pode modificar o script para incluir ou excluir tipos específicos de arquivos, alterar a formatação do documento ou adicionar informações extras conforme necessário.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

# Objeto de estudo com API e Docker

## Execução (Código Fonte)

Faça uma API em JavaScript/NodeJS implementada em Docker na AWS para extrair  informações relevantes de um site com conteúdo em formato RSS. Esta aplicação deve salvar os dados em arquivo JSON dentro de um bucket S3, e permitir a consulta do conteúdo salvo através de uma página html.

**Especificações**:

1. Escolher um site de conteúdo público com RSS (como notícias, blogs, etc. e **deve ser diferente das demais equipes**);
2. Desenvolver uma API para extrair parte o conteúdo RSS do site;
3. Salvar o conteúdo extraído em arquivo JSON;
4. Subir esta API utilizando Docker;
5. Criar uma página html para fazer consultas à API construída em NodeJS (pode ser bem simples, o layout não será avaliado).

* Exemplo de RSS com NodeJS:
  * [Create an RSS Reader in Node](https://sabe.io/tutorials/rss-reader-node)

### Docker

Execução em Docker, dentro da AWS Cloud.

* Subir o projeto NodeJS em Docker.
* O grupo pode ficar livre quanto à estratégia adotada para executar o Docker.

***

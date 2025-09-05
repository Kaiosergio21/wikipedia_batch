# Wikipedia Article Scraper

Este script permite baixar parte do conteúdo de um artigo da **Wikipedia** em português e salvar em um arquivo **Word (.docx)**.

Você pode escolher a porcentagem de parágrafos que deseja salvar e a direção (de cima para baixo ou de baixo para cima).

---

## Funcionalidades

- Busca artigos da Wikipedia pelo título.
- Seleciona parágrafos do artigo de acordo com a porcentagem definida pelo usuário.
- Remove referências do tipo `[1]`, `[2]`, etc.
- Salva o conteúdo em um documento Word (`.docx`) com o título do artigo.

---

## Pré-requisitos

- Python 3.x
- Bibliotecas Python:
  - `requests`
  - `beautifulsoup4`
  - `python-docx`

Instale as bibliotecas usando:

```bash
pip install requests beautifulsoup4 python-docx

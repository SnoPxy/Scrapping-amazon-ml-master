# Projeto de Web Scraping - Mercado Livre e Amazon

## Descrição do Projeto
Este projeto é uma ferramenta de Web Scraping desenvolvida em Python com interface gráfica utilizando o customtkinter. Ele permite que os usuários busquem produtos nos sites Mercado Livre e Amazon, exibindo os resultados de maneira interativa e visualmente atraente.

### Funcionalidades Principais
- **Busca de Produtos**: Realiza pesquisas nos sites Mercado Livre e Amazon.
- **Interface Gráfica**: Uma interface intuitiva que permite selecionar o site e visualizar os resultados.
- **Exibição de Resultados**: Mostra links, descrições e preços dos produtos em uma nova janela.
- **Apresentação do Programa**: Um frame inicial personalizado com o propósito do programa, opções de busca e botão de envio.

## Tecnologias Utilizadas
- **Python**
- `Selenium` para extrair informações das páginas HTML.
- **customtkinter** para criar a interface gráfica interativa.

## Como Usar
1. **Configuração do Ambiente**:
   - Certifique-se de ter o Python instalado.
   - Instale as bibliotecas necessárias com o comando:
     ```bash
     pip install requests selenium customtkinter
     ```

2. **Execução do Programa**:
   - Execute o script principal do projeto.
   - Escolha o site (Mercado Livre ou Amazon) na interface gráfica.
   - Insira o termo de busca e pressione o botão de envio.
   - Os produtos serão importados para um planilha no excel, com o preço, descrição e o link propriamente dito. 

## Estrutura do Projeto
```
projeto/
|-- main.py                # Arquivo principal do programa.
|-- scraping/
|   |-- mercado_livre.py   # Script de scraping para o Mercado Livre.
|   |-- amazon.py          # Script de scraping para a Amazon.
|-- interface/
    |-- app.py            
```

## Personalização da Interface
- Texto de apresentação inicial: "**Busque produtos nos sites**" .
- Opções para selecionar o site de busca (Mercado Livre ou Amazon).

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias ou novas funcionalidades.

## Autor
Arthur Lopes

---

### Observação
Este projeto foi desenvolvido com fins educacionais e segue os Termos de Uso dos sites Mercado Livre e Amazon. Certifique-se de respeitar as políticas de uso das plataformas ao utilizar este programa.
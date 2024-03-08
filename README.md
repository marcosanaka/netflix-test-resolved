# Bootcamp de Python para Análise de Dados - Projeto

## Visão Geral do Projeto

Este projeto faz parte do Bootcamp de Python para Análise de Dados oferecido pela DIO (Digital Innovation One). O código fornecido tem como foco o processamento de arquivos Excel dentro de uma pasta especificada e a consolidação dos dados em um formato limpo e organizado.

## Estrutura do Projeto

A estrutura do projeto é a seguinte:

pasta-do-projeto/
│
├── src/
│ ├── data/
│ │ ├── raw/
│ │ └── ready/
│ └── script.py
│
└── README.md

- **src/:** Contém o código-fonte do projeto.
  - **data/:**
    - **raw/:** Diretório contendo os arquivos Excel brutos.
    - **ready/:** Diretório para o arquivo Excel de saída limpo e processado.
  - **script.py:** Script Python para processar e limpar os dados.

## Como Usar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório em sua máquina local.


```
git clone https://github.com/marcosanaka/netflix-test-resolved.git

cd nome-do-repositorio/src ```
```
1. Coloque seus arquivos Excel com os dados a serem 2.  2. processados no diretório src/data/raw/.

Execute o script:
```
python script.py
```
Se aplicável, os dados limpos e processados serão salvos como clean.xlsx no diretório src/data/ready/.
Convenção de Nomenclatura de Arquivos
O script identifica a localização e as informações da campanha com base em palavras-chave nos nomes dos arquivos. Siga uma convenção de nomenclatura como:

brasil: Indica dados relacionados ao Brasil.
france: Indica dados relacionados à França.
italian: Indica dados relacionados à Itália.
Dependências
pandas
os
glob

Instale as dependências necessárias usando o seguinte:

```
pip install pandas
```

Contribuições
Sinta-se à vontade para contribuir, enviando problemas ou solicitações de pull.

Licença
Este projeto está licenciado sob a Licença MIT.

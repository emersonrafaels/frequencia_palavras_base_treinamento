
<h1 align="center">
    <img alt="Frequência de Palavras" title="#wordsfrequency" src="./assets/banner.png" />
</h1>

<h4 align="center"> 
	🚧 Frequência de Palavras 1.0 🚀 em desenvolvimento... 🚧
</h4>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/emersonrafaels/ocr_rg?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/emersonrafaels/frequencia_palavras_base_treinamento">

  	
  <a href="https://www.linkedin.com/in/emerson-rafael/">
    <img alt="Siga no Linkedin" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
	
  
  <a href="https://github.com/emersonrafaels/frequencia_palavras_base_treinamento/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/emersonrafaels/frequencia_palavras_base_treinamento">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/emersonrafaels/frequencia_palavras_base_treinamento/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/emersonrafaels/frequencia_palavras_base_treinamento?style=social">
  </a>
</p>


## 💻 Sobre o projeto

📦 **Frequência de palavras** é um projeto que obtém a **frequência* com que as **palavras** são **mencionadas nos comentários de uma base de treinamento**. 

A frequência de uma palavra ou **frequência de um termo (tf)** é uma **questão central na mineração de dados**.

## 🛠  Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python]

## ✍️  Técnicas utilizadas

 - **Tokenização** - É o processo de segmentar o texto em _tokens_, que são as formas mais elementais (geralmente palavras e pontuação) que carregam significado. O processo de tokenização deve levar em consideração detalhes como, por exemplo, se determinada pontuação indica ou não separação de tokens. Por exemplo, na frase _“Vou viajar pra N.Y.”_, o segmento _N.Y._ indica a entidade _Nova York_, e deve ser considerado um único token. Os modelos disponíveis no spaCy permitem essa tokenização especializada, produzindo resultados altamente adequados para as tarefas seguintes.
 - **Lematização** - Esse processo reduz as flexões das palavras ao seu _lemma_ ou raiz. Por exemplo, a palavra no plural _aviões_ é derivada do lemma _avião,_ assim como o verbo _assistimos_ tem origem no lemma _assistir._ A lemmatização costuma simplificar e generalizar os resultados de algumas tarefas de PLN posteriores.
 - **Remoção das Stop Words** - As stop words são atualmente as mais comuns em uma língua (como artigos, preposições, pronomes, conjunções, etc) e não trazem informações úteis ao texto. Exemplos de stopwords são: 'de', 'do', 'e', 'então'.
 - **Remoção de pontuações** - Como contarem a frequência de palavras, é útil remover as pontuações, evitando que elas sejam consideradas palavras.

## 🚀 Como executar o projeto

1. **Instalando**: pip install -r requirements.txt
2. **Executar o jupyter: Frequencia de palavras - Base de Treinamentos.ipynb**:

Os seus **parâmetros** estão na **etapa 2 - Variáveis Globais**:

```python
LANGUAGE = "portuguese"
CAMINHO_BASE_DADOS = r'BASE\BASE_TREINAMENTO.xlsx'

# NOME DAS COLUNAS DO DATAFRAME

NAME_COLUMN_MODULO = 'Selecione o treinamento que você participou recentemente:'
NAME_COLUMN_FRASES = 'Compartilhe conosco seus comentários, sugestões ou elogios com o treinamento.'

# NOME DAS COLUNAS TARGET

NAME_COLUMN_RESULT_MODULO = 'MÓDULO'
NAME_COLUMN_FRASES_POS_PROCESSING = 'COMENTARIOS_POS_PROCESSING'
NAME_COLUMN_WORDS_RAW = 'PALAVRAS'
NAME_COLUMN_WORDS_FREQUENCY = 'FREQUENCIA_PALAVRA'

# DEFININDO A QUANTIDADE DE PALAVRAS MAIS FREQUENTES DESEJADAS

QUANTIDADE_MAIS_FREQUENTES = 100

# CONFIGURANDO A VISUALIZAÇÃO DOS DATAFRAMES

pd.set_option('display.max_rows', 10)
pd.set_option('display.max_columns', 500)
pd.set_option('display.width', 1000)
```


## ➊ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas (O download pode ser realizado pela própria página do Python ou Anaconda):
[Python](https://www.anaconda.com/products/individual).

## 📝 Licença

Este projeto está sob a licença MIT.

Feito com ❤️ por **Emerson Rafael** 👋🏽 [Entre em contato!](https://www.linkedin.com/in/emerson-rafael/)

[Python]: https://www.python.org/downloads/
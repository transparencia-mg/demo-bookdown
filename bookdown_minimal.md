# INSTRUÇÕES PARA A CRIAÇÃO DO BOOKDOWN

## CONFIGURAÇÕES DE ARQUIVOS E PASTAS

### INDEX

Crie o arquivo index.md 

O arquivo index.md é a página principal que armazena dados sobre o bookdown. Nesse capítulo também pode conter a Introdução, logo após os dados do Index. 

Informe no arquivo INDEX os seguintes dados:

---
title: "título do arquivo"

author: "autor do arquivo"

site: bookdown::bookdown_site

documentclass: book

github-repo: "informe o endereço do repositório do github, se houver"

---

### READ.ME

Crie o arquivo README.md e descreva o conteúdo do seu bookdown.

Pode ser apenas uma linha.

### CAPÍTULOS

Escreva cada capítulo do book em um arquivo markdown.

Essa opção permite configurar o google analytics para cada capítulo/página do seu bookdown.

Não utilize a numeração para capítulos.

### .GITIGNORE

Crie na raiz do seu projeto um arquivo .gitignore no bloco de notas(txt) para indicar quais arquivos ou tipos de arquivos que não devem ser rastreados para o versionamento.

No arquivo .gitignore informe os arquivos que não serão versionados.

Basta listar os arquivos no gitignore e naturalmente eles serão ocultados.

### STATIC

Crie uma pasta denominada static

Nessa pasta armazene todos os arquivos de imagens, Power point e pdf que farão parte do seu bookdown.


#### Inserir imagens/arquivos

Para inserir a imagem no texto ou outros arquivos no seu texto markdown, utilize: 
![](static/nomedaimagem.nomedaextensao)

- Nome da imagem: nome do arquivo da imagem/arquivo salvo na pasta static
- Nome da extensão: nome da extensão da imagem/arquivo salvo na pasta static, exemplo:
  - .png
  - .jpg 

## FORMATAÇÃO DE TEXTO COM MARKDOWN 

- Negrito: **negrito** (utilize as palavras entre ** ** para formatar em negrito
- Itálico: *itálico* (utilize as palavras entre * * para formatar em itálico)
- Lista com marcadores: utilize: "-"
  - 1
  - 2
  - 3
  
- Cabeçalho: utilize # para criar cabeçalhos
# Cabeçalho nível um
## Cabeçalho nível dois
### Cabeçalho nível três
### E assim por diante
  

- Links: "[]()": [nome do link](endereço do link)


Após criar os capítulos do seu book, iniciaremos a criação do RPROJECT no Rstudio.

## CRIAR UM RPROJECT - RSTUDIO

A criação de um projeto do Rstudio permite dividir o trabalho em múltiplos ambientes, cada um com o seu diretório, documentos e workspace.

Para criar um projeto, clique em New Project... no Menu File. Na caixa de diálogo que aparecerá, clique em New Directory para criar o projeto em uma nova pasta ou Existing Directory para criar em uma pasta existente. Se você tiver o Git instalado, você também pode usar projetos para conectar com repositórios do Github e outras plataformas de desenvolvimento. Para isso, basta clicar em Version Control.

Após criar o RPROJECT, iniciaremos os passos para a consulta pública.

## CONSULTA PÚBLICA

Para a consulta pública, crie os seguintes arquivos.

### CONFIGURAÇÕES DE ARQUIVOS E PASTAS

### contribuing.md

Crie um arquivo Contribuing e descreva nesse texto como podem ser feitas as contribuições a consulta pública.

### terms-of-use.md

Crie um arquivo Terms of Use e descreva sobre as condições e regras para que um usuário do bookdown possa utilizar o serviço que está sendo oferecido.

## CONFIGURAÇÕES DE SISTEMAS

### hypothesis

Hypothes.is é um projeto de software de código aberto que visa coletar comentários sobre declarações feitas em qualquer conteúdo acessível pela web, filtrar e classificar esses comentários para avaliar a credibilidade de cada declaração.

#### Configuração



### google-analytics.html

O Google Analytics é um serviço gratuito oferecido pela Google no qual, ao ativar-se o serviço é possível receber um código para ser inserido na página cadastrada e, a cada exibição, estatísticas de visitação são enviadas ao sistema e apresentadas ao gestor do site.

#### Configuração

### style.css

CSS é chamado de linguagem Cascading Style Sheet e é usado para estilizar elementos escritos em uma linguagem de marcação como HTML. O CSS separa o conteúdo da representação visual do site. Pense  na decoração da sua página. Utilizando o CSS é possível alterar a cor do texto e do fundo, fonte e espaçamento entre parágrafos. Também pode criar tabelas, usar variações de layouts, ajustar imagens para suas respectivas telas e assim por diante.

#### Configuração

## FORMATOS DOS ARQUIVOS DO BOOKDOWN

### Makefile

O arquivo Makefile é utlizado para definir como vamos criar um formato de saída específico com base em um documento Markdown de origem.


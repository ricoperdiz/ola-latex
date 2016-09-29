# ola-latex
Curso despretensioso sobre latex, git e R destinado aos membros do grupo de pesquisa "[Ecologia e Evolução de Plantas da Amazônia](http://www.botanicaamazonica.wiki.br/labotam/doku.php?id=inicio)" do curso de pós-graduação em Botânica do INPA.

O objetivo é facilitar o trabalho em equipe na produção de trabalhos científicos, envolvendo tratamentos taxonômicos, comunidade arbórea, filogenia, biogeografia e filogeografia.

---------------

## Informações gerais

Data: 28-29 de setembro de 2016

Local: Sala de aula do PPGBOT-INPA

Horário: aulas pela tarde, 14:00-18:00 h

Quem vai ministrar: Ricardo Perdiz, doutorando PPGBOT INPA.


---------------

## Instruções de instalação

**TeX**

Para poder rodar o latex, é necessários que vocês tenham instalado em seus computadores alguma distribuição TeX. Desta forma, usuários:

+ Linux - instalem o TeXLive
+ Windows - instalem o MikTeX
+ Mac OS - instalem o [MacTeX](http://www.tug.org/mactex/)

Mais instruções de instalação podem ser encontradas [aqui](https://www.latex-project.org/get/).

Um aviso. Vocês verão que haverá a possibilidade de instalar um pacote básico, geralmente de ca. 500 Mb, e outro maior, de ca. 2 Gb. INSTALEM O MAIOR!

**R**

Tenham R instalado e atualizado em seus computadores.

Instalem e atualizem o RStudio.

Instalem os seguintes pacotes:

+ tidyverse
+ knitr
+ rmarkdown
+ magrittr

**git**


Instalem e atualizem o git no computador.

Vejam instruções [aqui](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).


**EXTRA**

Se vocês tiverem algum organizador de referência bibliográfica, atualizem. Se não tiverem, instalem. De preferência, que possam lidar com arquivos .bib (JabRef, Mendeley etc.).

Outra coisa importante é ter noções básicas de como usar o **Terminal** no Mac OS X ou Linux, ou o prompt de comando no Windows.  Tutoriais ou manuais podem ser encontrados em:

+ [Windows](http://www.cs.princeton.edu/courses/archive/spr05/cos126/cmd-prompt.html)
+ [Mac OS X](http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line)
+ [Linux](http://linuxcommand.org/)


---------------

## Dados

Baixem os dados disponíveis [aqui](http://www.botanicaamazonica.wiki.br/labotam/doku.php?id=alunos:r.perdiz:arquivos:inicio).

---------------

## Etapas do curso

Para passar os conhecimentos básicos de git e latex, decidi criar um repositório no GitHub. Assim, enquanto vocês aprendem o básico de latex e rmarkdown, escrevendo textos e scripts com R embutido, podemos aprender git propondo mudanças a este repositório.

Desta forma,o primeiro passo é realizar um 'fork' neste repositório. Após essa ação, o próximo passo é clonar este repositório em seu computador.

1. Efetuar um 'fork' do repositório **ola-latex** em sua conta GitHub.
1. Clonar o repositório **ola-latex** para seu computador.
1. Alterar os arquivos e propor mudanças.

### Como realizar um 'fork' do repositório?

1 Na página principal do repositório, aperte o botão **Fork** no canto direito da página.

Pronto! Você tem uma cópia deste repositório em sua página.

### Como clonar o repositório?

1. Abra o terminal ou prompt de comando e navegue para o local no seu computador onde você deseja criar uma cópia local do repositório.

1. Ao chegar no local desejado, antes de clonar o repositório, é necessário configurar o sistema para aceitar o proxy de nossa instituição. Para isso, digite os comandos abaixo:

````
git config --global http.proxy http[s]://NOMEdoUSUARIO:SENHA@PROXY:PORTA
````

Substitua os itens **NOMEdoUSUARIO**,**SENHA**,**PROXY**,**PORTA**, pelos valores respectivos. Isso permitirá efetuarmos o passo seguinte.

1. Na página principal do repositório, busque e aperte o botão **Clone or download** e copie o endereço aí exposto.

1. Digite `git clone` e cole o endereço que você copiou no passo acima:

```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

1. Pressione **Enter**. O clone local será criado.

### Como manter o seu 'fork' em sincronia com repositório original?

Ao fazer uma cópia de um repositório, você pode propor mudanças ao repositório original. Para isso, você deve configurar o Git para poder manter um link entre a origem e o seu clone de forma a sua cópia sempre esteja atualizada conforme a origem.

1. Na página original do repositório, copie o endereço que aparece ao clicar o botão **Clone or download**.

1. Navegue até a pasta do repositório em seu computador usando o terminal. 

1. Digite `git remote -v` e aparecerá na tela a conexão existente entre o seu computador e a origem do seu clone.

1. Digite então `git remote add upstream`, e então cole o endereço copiado em um item acima. Em nosso caso, será como exposto abaixo:

````
git remote add upstream https://github.com/ricoperdiz/ola-latex.git

````

### Propondo mudanças ao repositório original

EM CONSTRUÇÃO!


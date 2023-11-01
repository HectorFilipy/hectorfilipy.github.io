---
title: "6 Comandos Básicos Linux"
date: 2023-11-01T02:55:21+05:30
draft: false
github_link: "#"
author: "Hector Filipy"
tags:
  - Comandos
  - Linux
  - Tutorial
image: /images/post.jpg
description: ""
toc:
---

#6 Comandos Básicos do Linux

Olá tudo bem?

Venho trazer para vocês alguns comandos básicos do linux!

Se você ainda está aprendendo e se familiarizando com o Linux, acredito que o uso da interface de linha de comandos(CLI) é uma das coisas que mais assusta. Por isso, aprender os comandos básicos do Linux é normalmente, o primeiro passo para começar a dominar o sistema.

Para quem não sabe o que é um Terminal, resumindo em poucas palavras, trata-se de uma janela de comando para realizar tarefas com mais agilidade e possibilidades no Linux. A princípio parece muito assustador a ideia de abrir mão da interface gráfica(GUI) para alguns processos, porém a adaptação deve ser realizada aos poucos, visto que existem distros do Linux com mais foco em design, como o Mint, POP_OS e etc...

Pensando em ajudá-lo nessa questão, selecionei uma série de comandos de nível básico para você começar a praticar e entener que não é um bicho de 7 cabeças. Ao longo do estudo, você perceberá que os comandos são comuns na rotina de qualquer usuários, Portanto fiquem bem atentos aos 6 comandos que mostro a seguir.

##1 - CD

Este comando básico do Linux é que mais utilizamos para explorar diretórios por meio do terminal, seu nome é **Change Directory** por isso do **CD**. O comando ja fala por si só, ele nos permite navegar pelas pastas, mas de diferentes maneiras utilize o cd --help para ver mais sobre o comando.

Como exemplo, podemos acessar um diretório facilmente ao digitar o comando **cd** seguido do caminho que deseja acessar.

```bash
cd /home
```

Caso voce queira voltar um diretório antes é só digitar o **..**

```bash
cd ..
```

##2 - CAT

Uma das formas de criar arquivos por meio do terminal, sabemos que existem diferentes modos para isso, sendo um deles o comando **cat**. Com o cat, podemos tanto criar um ou mais arquivos quanto ver o conteúdo de um arquivo existente, entre outras coisas.

Como exemplo vamos ver como ler o conteúdo de um arquivo (/home/user/lista.txt, no caso):

```bash
cat /home/user/lista.txt

1-Banana
2-Maçã
3-Uva
4-Melão
5-Pêra
6-Abacaxi

```

Você consegue abrir quantos arquivos desejar, basta somente digitar o nome de cada um deles e o terminal exibirá. 

Vamos agora criar um arquivo, digite:

```bash
cat texto.txt
```

##3 - TOUCH

Mais um comando que é possivel criar arquivos, que de fato nem sempre criamos arquivos inserindo conteúdos neles. Em casos assim, usar o cat não é a melhor opção, pois, como aprendemos acima, a ferramenta abre os campos automaticamente para o usuário digitar. Portanto o comando touch é a escolha mais apropriada nessas horas.

Como exemplo vamos digitar;

```bash
touch texto1.txt texto2.txt texto3.txt
```

Digitando **touch --help** é possível consultar todas as opções existentes para o comando.

##4 - UPTIME

Esta listado entre os comandos básicos do Linux, o **uptime** é de muito importânte para os administradores de sistemas. Em uma única linha, ele nos informa o horário atual, há quanto tempo o sistema operacional está rodando, quantos usuários estão logados, e o tempo médio de carregamento do sistema.

o comando ficaria;

```bash
uptime

17:20:06 up  1:26,  2 users,  load average: 0,36, 0,43, 0,60
```

##5 - LS

O comando **ls** é utilizado para listar arquivos e diretórios do sistema. Se digitar o comando **ls** no terminal sem adicionar nenhuma opção, serão exibidos na tela todos os itens em formato básico.

Agora, se utilizarmos a opção **-l**, veremos os detalhes mencionados acima e outras informações, como data e hora de modificação e o proprietário do arquivo/diretório.

```bash
 ls -l
```

Mesmo assim ainda há arquivos que podem não aparecer nos resultados por conta deles serem ocultos. Para visualizarmos basta digitar **ls -a**.

Se quiser descobrir mais recursos existentes no comando, é só digitar

```bash
ls --help.
```

##6 - PWD

Por ultimo trago o comando **pwd** é comumente utilizado por administradores de sistemas para identificar o diretório atual. Ao digitarmos o comando, o terminal exibe o endereço completo do diretório. Exemplo:

```bash
pwd

/etc/apache2/
```






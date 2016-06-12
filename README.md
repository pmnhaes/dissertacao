# Dissertação
Dissertação para Engenharia de Produção (UENF)


Projeto criado para escrita da dissertação a ser apresentada como requisito obrigatório para obtenção de grau de Mestre em Engenharia de Produção na Universidade Estadual do Norte Fluminense Darcy Ribeiro - UENF.


# Compilando os arquivos .tex

Este trabalho de conclusão de curso foi feito utilizando LaTeX [#]_ , seguindo as principais orientações abnt-br. Mediante algumas modificações especiaficas para UENF.

# Pré requisitos

Para compilar os arquivos .tex é necessário a instalação do pacote *abntex*. Para isso, basta executar o seguinte commando em um terminal:

  $ sudo apt-get install abntex

Aconselha-se também a instalação do texlive para linux.

  $ sudo apt-get install texlive texlive-base texlive-latex-base texlive-lang-english texlive-lang-portuguese

# Instalando o *latexmk*

As únicas dependências do *latexmk* são o *TeX*, *LaTeX* e *Perl*.

Para instalar o script, bastar executar em um terminal:

    $ sudo cp latexmk.pl /usr/bin/latexmk

    $ sudo chmod a+rx /usr/bin/latexmk

Usando o *latexmk*
==================

Para gerar um .pdf a partir de um .tex utilizando o script, basta apenas executar em um terminal:

    $ latexmk -pdf nome_do_arquivo.tex

Para gerar indices para lista de siglas:

    $ makeindex nome_do_arquivo.nlo -s nomencl.ist -o nome_do_arquivo.nls

Para limpar arquivos gerados:

    $ rm *.aux tcc.bbl tcc.blg tcc.fdb_latexmk tcc.lof tcc.log tcc.out tcc.toc tcc.glo tcc.ilg tcc.lot


# Referências

* [Latex Project](http://www.latex-project.org/)
* [Quali Agil](http://github.com/qualiagil)
* [Latexmk](http://www.phys.psu.edu/~collins/software/latexmk-jcc/)

# Dissertação
Dissertação para Engenharia de Produção (UENF)


Projeto criado para escrita da dissertação a ser apresentada como requisito obrigatório para obtenção de grau de Mestre em Engenharia de Produção na Universidade Estadual do Norte Fluminense Darcy Ribeiro - UENF.


===========================
Compilando os arquivos .tex
===========================

Este trabalho de conclusão de curso foi feito utilizando LaTeX [#]_ , seguindo as principais orientações abnt-br. Mediante algumas modificações especiaficas para UENF.

Pré requisitos
==============

Para compilar os arquivos .tex é necessário a instalação do pacote *abntex*. Para isso, basta executar o seguinte comando em um terminal:

  $ sudo apt-get install abntex

Aconselha-se também a instalação do texlive para linux.

  $ sudo apt-get install texlive texlive-base texlive-latex-base texlive-lang-english texlive-lang-portuguese

Instalando o *latexmk*
======================

As únicas dependências do *latexmk* são o *TeX*, *LaTeX* e *Perl*.

Para instalar o script, bastar executar em um terminal:

    $ sudo cp latexmk.pl /usr/bin/latexmk

    $ sudo chmod a+rx /usr/bin/latexmk

Usando o *latexmk*
==================

Para gerar um .pdf a partir de um .tex utilizando o script, basta apenas executar em um terminal:

    $ latexmk -pdf nome_do_arquivo.tex


# Referências

* [ppa:saiarcot895/myppa(for Ubuntu 14.04 and later versions)](https://launchpad.net/~saiarcot895/+archive/ubuntu/myppa)
* [ppa:apt-fast/stable(out of date, for Ubuntu 11.04~13.10)](https://code.launchpad.net/~apt-fast/+archive/stable)

* [Latex Project](http://www.latex-project.org/)
* [Quali Agil](http://github.com/qualiagil)
* [Latexmk](http://www.phys.psu.edu/~collins/software/latexmk-jcc/)

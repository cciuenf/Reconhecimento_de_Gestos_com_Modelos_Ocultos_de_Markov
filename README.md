# Reconhecimento de Gestos Utilizando Cadeias Ocultas de Markov 

Este projeto é o controle de versão da minha monografia do curso de graduação em
Ciência da Computação da Universidade Estadual do Norte Fluminense (UENF).

# Dependências

Para poder compilar, algumas dependências devem ser instaladas no seu sistema.
As dependências são baseadas na distribuição Linux Ubuntu.

    sudo apt-get install texlive-latex-base abntex texlive-fonts-recommended texlive-lang-portuguese

# Compilando

Para compilar, depois ter instalado as dependências, basta rodar o comando
`make` ou `make pdf`.

Se encontrar o erro `LaTeX Error: File fncychap.sty not found`, instale também.

  sudo apt-get install latexmk texlive texlive-science texlive-formats-extra

Antes de efetuar um commit execute o comando `make clean` para remover arquivos temporários (e o pdf).

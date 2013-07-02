slideskde
=========

Modelo de apresentação em LaTeX/Beamer sobre o KDE.

Para rodar, em qualquer sistema Linux:

UTILIZANDO O KDE/KILE:
----------------------

1) Instale o Kile, caso ainda não esteja instalado. Com esse passo, você garante a instalação dos pacotes 
necessários para rodar o LaTeX e gerar a apresentação em PDF.

2) Abra o arquivo slideskde.tex no Kile.

3) No menu principal, vá até Build -> Compile -> PDFLaTeX

4) Vá até Build -> View -> ViewPDF para abrir o PDF resultante no visualizador de PDF configurado.

SEM UTILIZAR O KILE:
--------------------

1) Verifique a disponibilidade do LaTeX e do pacote Beamer. Em quase todas as distribuições é possível 
instalar um pacote chamado TeXLive que contém os pacotes padrão (incluindo o beamer, para apresentações).

2) Salve o arquivo slideskde.tex em um diretório de sua preferência.

3) Vá até o diretório em que o arquivo slideskde.tex está salvo e digite

$ pdflatex slideskde.tex

4) Abra o arquivo slideskde.pdf no seu visualizador de PDF favorito :)

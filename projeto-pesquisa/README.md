# Modelo LaTeX de Projeto de Pesquisa para o [PPGCA](http://dcm.ffclrp.usp.br/ppgca/)

Este diretório contém uma [classe](ppgca.cls) LaTeX para ser carregada e um 
[arquivo](main.tex) exemplo de projeto de pesquisa para o programa de pós-graduação 
em Computação Aplicada do Departamento de Computação e Matemática da FFCLRP/USP.

## Receita

Baixe o conjunto de arquivos
[=>zipado<=](https://git.uspdigital.usp.br/ajholanda/modelos-ppgca/repository/archive.zip),
e descompacte-os em um diretório qualquer. Dentro do diretório
descompactado, entre no diretório `projeto-pesquisa/`, os arquivos
principais serão:

- [preppgca.cls](preppgca.cls) - classe LaTeX a ser carregada;
- [main.tex](main.tex) - arquivo LaTeX a ser editado;
- [refs.bib](refs.bib) - arquivo bibtex onde as referências bibliográficas devem ser inseridas.

Edite o arquivo [main.tex](main.tex), alterando-o conforme a
necessidade da dissertação. Adicione as referências bibliográficas no
arquivo [refs.bib](refs.bib). Execute o comando `pdflatex` ou
`xelatex`, depois execute o bibtex.  É preciso executar o `pdflatex`
ou `xelatex` mais duas vezes para acertar as referências
bibliográficas. Se a bibliografia não for alterada daqui em diante,
não é preciso mais executar o bibtex e o comando `pdflatex` ou
`xelatex` podem ser executados somente uma vez. Após a compilação será
gerado um arquivo nomeado [main.pdf](main.pdf).

### Overleaf

O projeto também pode ser editado no
 [Overleaf](https://www.overleaf.com/latex/templates/pmkrzphywfqp/clone)
 a partir do link
 [https://www.overleaf.com/latex/templates/pmkrzphywfqp/clone](https://www.overleaf.com/latex/templates/pmkrzphywfqp/clone). Ao
 clonar o projeto escolha o programa (_engine_) `xelatex` para
 compilar o arquivo principal, pois algumas fontes podem ocasionar
 erro ao serem carregadas pelo programa (_engine_) `latex`.


## Fontes

A seguinte fonte foi utilizada para a confecção do modelo em LaTeX:

- [Diretrizes do DCM/FFCLRP/USP](http://dcm.ffclrp.usp.br/ppgca/documentos/Diretrizes_Projeto_Pesquisa.pdf).

# djpdf v1.1
Script para manipulação de arquivos PDF

## Requisitos de instalação
* pdftk
* dialog
* tesseract-ocr
* tesseract-ocr-por
* tesseract-ocr-eng
* imagemagick
* Scripts **djpdf** e **pdfpcr** devem estar no mesmo diretório
* Scripts **djpdf** e **pdfpcr** devem ser executáveis
* Permissão de escrita no diretório dos scripts

## Funções do script (menu)
1) Dividir um arquivo PDF em várias páginas
2) Unir 2 ou mais arquivos PDF em um só arquivo
3) Transformar arquivo PDF comum em um arquivo PDF OCR
4) Converter imagens em PDF
5) Girar o arquivo PDF em 90º (sentido horário)
6) Girar o arquivo PDF em 90º (sentido anti-horário)
7) Girar o arquivo PDF em 180º
8) Separar páginas pares e ímpares de um arquivo PDF
9) Copiar arquivos e renomear de forma sequencial crescente

## Dicas
1) Instalando via **apt-get** de uma só vez todos os softwares necessários para o funcionamento do script:

_sudo apt-get install -y pdftk dialog tesseract-ocr tesseract-ocr-por tesseract-ocr-eng imagemagick_

2) Transformando os arquivos de script em executáveis (executar na pasta dos scripts):

_sudo chmod a+x djpdf pdfocr_

3) Automatizando a chamada do script (basta digitar **djpdf** sem a necessidade de apontar para o caminho arquivo)

_sudo ln -s [caminho_completo_do_arquivo_djpdf] /usr/sbin/djpdf_
Instruções de uso do Front-End do MVP3 do aluno Felipe Florêncio de Andrade

Para visualizar o front, basta fazer o download de todos os arquivos presente no diretório do Git Hub e abrir o arquivo "index.html", dessa forma já é possível visualizar toda a construção do front-end.

Para o download é possível baixar todos os arquivos em um único arquivo com formato compactado (.rar), ou baixar os arquivos separadamente que são os demais arquivos presentes nesse diretório.

A parte complementar do projeto referente ao Back-End esta presente no outro diretório do Git Hub: https://github.com/S3GFelipe/MVP3-Back.git



Sobre o Docker

Como executar através do Docker
Certifique-se de ter o Docker instalado e em execução em sua máquina.

Navegue até o diretório que contém o Dockerfile no terminal e seus arquivos de aplicação e Execute como administrador o seguinte comando para construir a imagem Docker:

$ docker build -t nome_da_sua_imagem .
Uma vez criada a imagem, para executar o container basta executar, como administrador, seguinte o comando:

$ docker run -d -p 8080:80 nome_da_sua_imagem
Uma vez executando, para acessar o front-end, basta abrir o http://localhost:8080/#/ no navegador.
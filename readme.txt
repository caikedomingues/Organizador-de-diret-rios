                                Organizador de diretórios

                                Objetivos do Sistema

-> O script deve verificar a pasta de downloads e transferir os arquivos para uma pasta especifica de acordo com a extensão
do arquivo.

-> O sistema deverá identificar as seguintes extensões: PDF, DOCX, XLSX, PPTX, ZIP, JPG, PNG, EXE e TXT

-> O sistema ira conter um código que cria as pastas padrões do sistema.
Dessa forma, você não precisará criar as pastas manualmente.

-> O sistema deverá verificar se o arquivo ja existe na pasta de destino antes
de realizar a transferência

-> O sistema deverá ter uma pasta que irá conter arquivos com extensões não identificadas

-> O sistema deverá permitir que um usuário possa adicionar uma nova extensão
no arquivo json sistema. Ao criar uma nova extensão, o sistema ira criar a pasta de forma automática

-> O sistema deverá retornar uma lista com os arquivos que ja existem nas pastas de destino.

                            Como utilizar o sistema 

-> 1° Passo: Baixe todos os arquivos (inclusive o arquivo json que contém 
as extensões padrão do sistema) 

-> 2° Passo: Salve todos os arquivos na pasta de sua escolha

-> 3° Passo: Execute o arquivo CriarPastasPadroes.ipynb. Esse arquivo irá
criar na pasta que você escolheu na etapa anterior os diretórios padrão
que irão conter cada arquivo.

-> 4° Passo: Após criar os diretórios padrão, acesse o arquivo "Organizador.ipynb" e  cole na variável "pasta download"o caminho da sua pasta de downloads.

5° passo: Após definir o caminho da sua pasta, execute todos os trechos
do arquivo "organizador.ipynb". Observação: o campo de adicionar
nova extensão é opcional, ou seja só execute-o caso queira inserir novos
formatos de arquivos no sistema.


                                    Arquivos do sistema
-> CriarPastasPadroes.ipynb: Ira conter o código que cria diretórios padrão

-> extensões.json: Ira conter as extensões padrões e as extensões adicionadas pelo usuário.

-> Organizador.ipynb: Ira conter o código que organiza os arquivos.
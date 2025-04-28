# Guia para uso e consolidação dos comandos e conceitos de Git e Github

## --- O que é Git?

Git é um software de versionamento de código, criado como um repositório local que guarda e gerencia diferentes pastas com diferentes versões de um arquivo.

## --- O que é Github?

Github é um serviço e rede social de versionamento de sites e arquivos, com foco na comunidade de programação e cria repositórios remotos para esses arquivos versionados.

### --- Comandos de manipulação básica de arquivos para o uso de Git e Github

* *git init*

> Cria um repositório local no lugar onde você estiver no terminal

* *git status*

> Verifica o estado dos arquivos e se eles estão preparados para serem commitados ao repositório remoto

* *git add + **arquivo*** 

> Adiciona arquivos específicos ou todos os arquivos para o estado de prepação antes do commit

* *git commit **-m""***

> Commita os arquivos, criando um versionamento do estado em que o arquivo estava no repositório

* *git remote add origin **ou** git remote add + link*

> Faz uma ligação do repositório local com o remoto, para os versionamentos estarem presentes no git e github

* *git push -u origin*

> Faz o rastreamento de um repositório remoto para enviar os commits de um arquivo ao repositório remoto (Feito só uma vez, depois é somente "git push")


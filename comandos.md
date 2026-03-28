# Comandos Linux

## ls
Lista arquivos

Exemplo:
ls -la

## cd
Muda de diretório

Exemplo:
cd /home

## pwd
Mostra diretório atual

## touch
Cria arquivos vazios

Exemplo:
touch arquivo.txt

## nano
Editor de texto no terminal. Cria ou edita arquivos diretamente pelo terminal

Comportamento ao salvar:
- Ao usar CTRL + 0, o nano pede o nome do arquivo para salvar
- Se você mantiver o mesmo nove, ele salva no arquivo que você abriu/está editando
- Se você alterar o nome, ele salva em um novo arquivo
- Se o nome informado não existir, ele cria um arquivo com esse nome
- Se você abrir um arquivo existente e salvar com outro nome, você estará criando uma cópia com 
outro nome (não alterando o original)
- Se for salvar em um arquivo que está em outra pasta predciso digitar o caminho até o arquivo

Exemplo:
- Abrir: nano arquivo.txt
- Salvei como arquivo.txt -> atualiza o mesmo arquivo
- Salvei como novo_arquivo.txt -> salva mudanças em novo_arquivo.txt/
se não existir novo_arquivo.txt cria um com este nome (nestes dois casos arquivo.txt permanece
inalterado)

##cat
Exibe o conteúdo de arquivos no terminal sem abrir o editor

Exemplo:
cat arquivo.txt

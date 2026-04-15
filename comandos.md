# Comandos Linux

## ls
Lista arquivos

Exemplo:
ls -la

- -l detalhado
Mostra detalhes do arquivo (permissões, dono, tamanho, data)

- -a inclui arquivos ocultos

Dica extra:
ls -lh

- tamanhos legíveis(KB,MB)

## cd
Muda de diretório

Exemplo:
cd /home

Complementos importantes:

cd ..
- volta uma pasta

cd ~
- vai para home


## pwd
Mostra diretório atual

*origem: print working directory*

## touch
Cria arquivos vazios

Exemplo:
touch arquivo.txt

## nano

Editor de texto no terminal. Cria ou edita arquivos diretamente pelo terminal.

### Comportamento ao salvar:

Ao usar `CTRL + O`, o nano pede o nome do arquivo para salvar.

- Se você mantiver o mesmo nome, ele salva no arquivo que você abriu/está editando.
- Se você alterar o nome, ele salva em um novo arquivo.
- Se o nome informado não existir, ele cria um arquivo com esse nome.
- Se você abrir um arquivo existente e salvar com outro nome, você estará criando uma cópia com outro nome (não alterando o original).
- Se for salvar em um arquivo que está em outra pasta, é preciso digitar o caminho até o arquivo.

### Exemplo:

- Abrir: `nano arquivo.txt`
- Salvar como `arquivo.txt` → atualiza o mesmo arquivo
- Salvar como `novo_arquivo.txt` → salva as alterações em `novo_arquivo.txt`

Se o arquivo não existir, ele será criado.  
Nos dois últimos casos, `arquivo.txt` permanece inalterado.

---

## cat

Exibe o conteúdo de arquivos no terminal sem abrir um editor.

Exemplo:

```bash
cat arquivo.txt
```
*origem: concatenate*

## mkdir

Cria diretórios (pastas)

- Exemplo: mkdir nome_pasta

## mv

Move ou renomeia arquivos e diretórios

- Exemplo: `mv arquivo.txt pasta/`
- Exemplo: `mv antigo.txt novo.txt`

## cp

Copia arquivos

- Exemplo: `cp arquivo.txt copia.txt`
- Exemplo: `cp arquivo.txt pasta/`

## rm

Remove arquivos

- Exemplo: `rm arquivo.txt`
- Exemplo: `rm -i arquivo.txt` *pede confirmação*

## chmod

Altera permissões de arquivos

Permissões:  
- r = leitura
- w = escrita
- x = execução

Valores:  
- 4 = leitura
- 2 = escrita
- 1 = execução

- Exemplo: `chmod 644 arquivo.txt`
- Exemplo: `chmod 600 arquivo.txt`
- Exemplo: `chmod +x script.sh`

## git status

Mostra o estado dos arquivos no repositório

- Exemplo: git status

## git add

Adiciona arquivos para o commit

- Exemplo: `git add .`  
*ponto = tudo que está na pasta atual*

## git commit

Salva as alterações localmente

- Exemplo: `git commit -m "mensagem"`

## git push

Envia as alterações para o GitHub

- Exemplo: `git push`

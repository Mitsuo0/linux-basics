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

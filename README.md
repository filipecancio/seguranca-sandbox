# seguranca-sandbox

Digite o comando abaixo:

```bash
gpg -a --export -e 'filipe.cancio@gmail.com' > mykey.asc
```
Digite o comando abaixo:

```bash
gpg --export filipe.cancio@gmail.com > mykey.asc
```
```
Digite o comando abaixo:

```bash
gpg -e -a -r filipe.cancio@gmail.com message.txt
```
```
Digite o comando abaixo:

```bash
gpg  --decrypt exemplo.txt.asc > exemplo.txt
```
Digite o comando abaixo:

```bash
gpg --import mykey.asc
```
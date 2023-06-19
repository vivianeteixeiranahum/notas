# inicializando git local

Primeiro confira se o git está instalado verificando a versão:
```bash
git --version
```
Depois configure o usuário do git:

```bash
git config --global user.name "seu nome" 
```
Agora você vai fazer a inicializção local:

```bash
cd documents.
esse passo acessa a pasta documents
´´´
```
mkdir notas
esse comando cria uma nova pasta.
```
```
cd notas: -
 esse comando 
 execulta a pasta que você criou para dentro da pasta já existente
```
 #COMANDOS DO GIT
```
git status:
Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.
```
```
git add <filename ou.>:
Esse comando realiza a inclusão ou modificação do arquivo no diretório local, preparando ele para ser entregue ao servidor remoto para a mesma aplicação que está sincronizada na máquina local.
```
```
git restore --staged <filemane ou .>:
O comando git revert pode ser considerado um comando do tipo "desfazer"; no entanto, ele não é uma operação tradicional de desfazer.
```
```
git branch <branchname>:
O comando git branch permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo.
```
```
git checkout <branchname>:
- Mudar de branch. Quando o git muda de branch, todas as alterações que foram aplicadas na branch serão substituídas pelas alterações da branch que foi feito o checkout.
```
```
git checkout-b <branchname>:
Para criar e fazer o checkout para uma nova branch com um único comando, você pode usar: git checkout -b NOME-DA-NOVA-BRANCH Isso o levará automaticamente para a nova branch. Fazer o checkout para uma nova branch ou redefinir uma branch para seu ponto inicial
```
```
git commit-m <description>:
Um comando de atalho que cria de imediato um commit com uma mensagem de commit transmitida. Por padrão, git commit abre o editor de texto configurado no local e solicita que uma mensagem de commit seja escrita.
```
```
git push:
O comando git push é usado para gravar em um repositório remoto. 
```
```
git bruch -D<brachname>:
O comando git branch permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo.
```
```
git fesh:
 git fetch é um comando básico usado para baixar conteúdos de um repositório remoto
```
```
git pll:
 O git pull é um dos muitos comandos que têm a responsabilidade de "sincronizar" conteúdo remoto....
 ```
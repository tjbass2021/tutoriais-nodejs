# Atualizando o NodeJs para sua versão mais atual no Linux

Para fazer a atualização é bastante simples. Precisaremos primeiro 
instalar o 'módulo n' com o npm, que é o gerenciador de pacotes do 
NodeJS.

Para isso, use o comando:

~~~bash
sudo npm install n -g
~~~

A flag '-g' é adicionada para indicar que queremos fazer a instalação do 
módulo de forma global em nosso sistema.

Agora é possível instalar a versão estável mais recente com o comando:

~~~bash
sudo n stable
~~~

E a versão mais recente (não estável):

~~~bash
sudo n latest
~~~

Pronto. Para verificar se a versão está atualizada, use:

~~~bash
node --version
~~~

Onde será retornada a versão instalada no sistema.

--- 
Este artigo foi escrito baseado em uma questão do QAStack. Link da 
dúvida original: [Atualizando o Node.js para a versão mais 
recente](https://qastack.com.br/programming/10075990/upgrading-node-js-to-latest-version)

---
[Retornar ao índice principal](README.md)

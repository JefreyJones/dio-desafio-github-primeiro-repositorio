## <u>Introdução ao Git e ao GitHub</u>

#### Instrutor: Otávio Reis



#### Principais características:

- Controle de versão;
- Armazenamento em nuvem;
- Trabalho em equipe;
- Melhorar o seu código;
- Reconhecimento.



#### - Elementos -

**Encriptação** -  O sha1, um algoritmo de encriptação (hash seguro).  A encriptação gera um conjunto de caracteres identificador de 40 dígitos.  Para gerar um código para um arquivo; no terminal do git, digite: **`openssl sha1 "nome do arquivo"`**.



**Objetos fundamentais** - Três tipos  básicos de objetos responsáveis pelo versionamento do nosso código: ***blobs, trees e commits***.



#### - Autenticação no GitHub -

**Chave SSH** - Forma de estabelecer uma conexão segura e encriptada ( com 2 chaves - 1 pública e 1 privada).

- Comandos para gerar as 2 chaves:  **`ssh-keygen -t ed25519 -c "meu email"`**
- Iniciar o ssh agent (entidade responsável por lidar com as chaves geradas): **`eval $(ssh-agent -s)`**
- Passar a chave privada para o ssh-agent: **`ssh-add "chave privada"`**



**Segunda forma: "Token de acesso pessoal"**



#### - Comandos -

**`git init`** - Inicializar um repositório.

**Obs:** se for a primeira vez a usar o Git, será necessário executar alguns comandos para realizar a configuração inicial:

- **`git config --global user.mail "meu e-mail"`**
- **`git config --global user.name "meu nome"`**



**`git add`** - envia os arquivos para a área de staging (área temporária).



**`git commit -m "texto identificador da alteração"`** - envia para o repositório local.



**`git push origin master`** - envia as alterações no repositório local, para o repositório no GitHub.



<u>**Após criar o repositório no GitHub**</u> é necessário apontar o seu Git para o caminho remoto no GitHub.  No Git, digite o comando: **`git remote add orign "caminho do seu repositório no GitHub"`**.

Em seguida, verifique o status com o comando: **`git remote -v`**.

**Obs:** caso as configurações de e-mail e user name no Git estejam diferentes do existente no GitHub, é possível ajustar, utilizando os seguintes comandos:

- Para visualizar as configurações atuais no Git: **`git config --list`**

- Caso seja necessário ajustar, por exemplo, o user name, use os comandos:

  **`git config --global --unset user.name`**

  **`git config --global user.name "nome correto"`**



<u>**Para puxar o seu conteúdo do GitHub, para o computador local**</u>: 

**`git pull origin master`**



<u>**Para clonar um repositório do GitHub**</u>: 

**`git clone "endereço do repositório"`**



<u>**Para criar uma nova Branch**</u>: 

**`git checkout -b "nome da branch"`**



<u>**Para retornar para a Branch Master**</u>: 

**`git checkout master`**



<u>**Para fazer um merge (juntar as Branches)**</u>: 

1 - retornar para a branch master: **`git checkout master`**

2 - realizar o merge: **`git merge "nome da branch"`**

3 - enviar para o GitHub: **`git push origin master`**



<u>**Para baixar o conteúdo de um repositório no GitHub para o repositório local:**</u>: 

**`git pull "endereço do repositório no GitHub"`**

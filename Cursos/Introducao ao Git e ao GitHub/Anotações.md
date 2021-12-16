## <u>Introdução ao Git e ao GitHub</u>

#### Instrutor: Otávio Reis



#### Principais características:

- Controle de versão;
- Armazenamento em nuvem;
- Trabalho em equipe;
- Melhorar o seu código;
- Reconhecimento.



#### - Elementos -

**Encriptação** -  O sha1, um algoritmo de encriptação (hash seguro).  A encriptação gera um conjunto de caracteres identificador de 40 dígitos.  Para gerar um código para um arquivo; no terminal do git, digite: ***openssl sha1 "nome do arquivo"***.

**Objetos fundamentais** - Três tipos  básicos de objetos responsáveis pelo versionamento do nosso código: ***blobs, trees e commits***.



#### - Autenticação no GitHub -

**Chave SSH** - Forma de estabelecer uma conexão segura e encriptada ( com 2 chaves - 1 pública e 1 privada).

- Comandos para gerar as 2 chaves:  ***ssh-keygen -t ed25519 -c "meu email"***

- Iniciar o ssh agent (entidade responsável por lidar com as chaves geradas): ***eval $(ssh-agent -s)***

- Passar a chave privada para o ssh-agent: ***ssh-add "chave privada"***



**Segunda forma: "Token de acesso pessoal"**








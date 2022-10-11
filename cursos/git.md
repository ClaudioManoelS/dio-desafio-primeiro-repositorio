# GIT E GITHUB

SHA1: Secure Hash Algorithm, é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de segurança nacional dos EUA). Conjunto de 40 caracteres.

Objetos Fundamentais

Sistema distribuído

Segurança

### Objetos GIT

- Blobs – Conteúdo dos arquivos acrescido de metadados para uso interno do git
- Trees – Pode apontar para um blob ou para outras trees
- Commits – Aponta para uma árvore, para um parente (antecessor), autor, mensagem e datahora

### Chaves SSH

- Autenticação via usuário e senha não será mais utilizado
- Chave SSH – Chaves públicas e privadas
- ssh-keygen -t ed25519 -C <email>
- Dentro da pasta /.ssh, copiar o conteúdo do arquivo de extensão.pub
- Usar o conteúdo do arquivo .pub para cadastrar a chave ssh no github
- eval $(ssh-agent -s) para iniciar o serviço
- ssh-add id_ed25519 para adicionar a identidade
- Ao clonar, usar o link no modo SSH

### Token

- No perfil, developer settings  Personal Access Token e gerar um novo token
- Clonar no modo https. No git mais recente será aberta uma tela solicitando o token de acesso

### Geral

ls -a – mostra arquivos ocultos

Git config –global –unset user.email

Ambiente Local: Working Directory -> Staging Area -> Local Repository

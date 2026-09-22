# Laboratório 1 (GIT/GitHub) - Chaves SSH :old_key:
---
Neste roteiro, será criada uma chave SSH para acesso ao repositório remoto do GitHub, através desse protocolo de transferência.

## Passo à Passo :footprints:

1. Caso ainda não possua, crie uma conta no [GitHub](https://github.com);
2. Em um terminal, crie um par de chaves assimétricas (_public_key_, _private_key_) co o seguinte comando (criando uma senha para as chaves locais): `ssg-keygen -t ed25519 -c "exemplo@email.com.br"` (substitua o e-mail de exemplo pelo e-mail usado no GitHub);
3. Copie o conteúdo da chave pública que estará em `~/.ssh/id_ed25519.pub`;
4. Abra o site de [configurações](https://github.com/settings/keys) ou clique no seu perfil > **settings**, **_SSH and GPG keys_**;
5. Clique em **_New SSH key_** e cole o conteúdo da chave pública. Dê um nome à chave (Exemplo: LabGrad) e salve;
    
    - *OBS*: Caso seja uma preocupação, lembre-se ao final de cad uso, de remover as chaves geradas na(s) máquina(s) local(is) e também no GitHub, repetindo esse processo esmpre que desejar realizar acessos ao Github dessa forma.

    Os comandos que realizaram esta tarefa:

    ```
    rm ~/.ssh/id_ed25519
    rm ~/.ssh/id_ed25519.pub
    ```

# Laboratório 2 - Desenvolvimento Colaborativo :busts_in_silhouette:

Neste roteiro, será simulado um desenvolvimento colaborativo de um projeto de software por uma equipe de ao menos duas pessoas desenvolvedoras, que chamaremos de **DevA** e **DevB**. No caso de mais pessoas na equipe, ajustar o roteiro.

---

## Passo à passo :footprints:

1. Verifiquem se o acesso ao [GitHub](https://github.com) está devidamente configurado (vide, o Laboratory 1);
2. **DevA** crie um repositório no Github e convide os demais colegas para participar no repositório: **Settings** > **Collaborators** > **Add People**;
3. **DevB**, aceite o convite clicando no perfil e indo em **Organizations**;
4. Clonem o repositório e suas máquinas locais;
5. **DevA**, adicione um arquivo de testo qualquer no repositório e faça _add_ _commit_ e _push_;
6. **DevB**, faça o _pull_, altere o arquivo e depois, faça _add_ _commit_ e _push_
7. **DevA** faça _pull_ para verificar a nova versão do arquivo (alterada pelo colega - **DevB**);
8. Usem `git log --graph` para visualizar os _commits_ e identificar os _commits_ feitos por cada um;
9. Façam alterações simultâneas no arquivo (em linhas diferentes). Em seguida, faça o _add_ e o _commit_;
10. Agora, um dos colegas (_Devs_) deve fazer o _push_ primeiro. Em seguida, o outro deverá fazer o _pull_, o que levará a visualização das modificações concorrentes e a necessidade de se realizar uma mesclagem (_merge commit_). Tentem resolver;
11. Após resolvido, usem o `git log --graph`para visualizar os _commits_, incluindo o _merge_ e identitifcar os _commits_ feitos por cada um;
12. Explore o Github para ver as várias informações que são passíveis de visualização, incluindo histórico completo e os vários _diffs_ nos _commits_, etc.;
13. Façam alterações em uma mesma linha e repitam o _push_ de um lado e o _pull_ do outro. Tentem fazer a mesclagem e resolver o conflito.
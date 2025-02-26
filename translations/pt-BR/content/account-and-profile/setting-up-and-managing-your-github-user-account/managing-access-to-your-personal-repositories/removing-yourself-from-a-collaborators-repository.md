---
title: Remover a si mesmo de um repositório de colaborador
intro: 'Se não desejar mais ser um colaborador no repositório de outro usuário, você poderá remover a si mesmo.'
redirect_from:
  - /leave-a-collaborative-repo
  - /leave-a-repo
  - /articles/removing-yourself-from-a-collaborator-s-repo
  - /articles/removing-yourself-from-a-collaborator-s-repository
  - /articles/removing-yourself-from-a-collaborators-repository
  - /github/setting-up-and-managing-your-github-user-account/removing-yourself-from-a-collaborators-repository
  - /github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/removing-yourself-from-a-collaborators-repository
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
  - Repositories
shortTitle: Remover-se
---

{% data reusables.user_settings.access_settings %}
{% ifversion fpt or ghec or ghes > 3.4 or ghae-issue-5658 %}
2. In the "Code, planning, and automation" section of the sidebar, click **{% octicon "repo" aria-label="The repo icon" %} Repositories**.
{% else %}
2. Na barra lateral esquerda, clique em **Repositories** (Repositórios). ![Guia Repositories (Repositórios)](/assets/images/help/settings/settings-sidebar-repositories.png)
{% endif %}
3. Clique em **Leave** (Sair) ao lado do repositório do qual deseja sair. ![Botão Leave (Sair)](/assets/images/help/repository/repo-leave.png)
4. Leia o aviso com atenção, depois clique em "I understand, leave this repository" (Eu compreendo, sair deste repositório). ![Caixa de diálogo avisando você para sair](/assets/images/help/repository/repo-leave-confirmation.png)

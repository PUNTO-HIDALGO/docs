---
title: Revisar suas chaves de implantação
intro: Você deve revisar as chaves de implantação para verificar se há chaves não autorizadas (ou potencialmente comprometidas). Você também pode aprovar as chaves de implantação que são válidas.
redirect_from:
  - /articles/reviewing-your-deploy-keys
  - /github/authenticating-to-github/reviewing-your-deploy-keys
  - /github/authenticating-to-github/keeping-your-account-and-data-secure/reviewing-your-deploy-keys
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Identity
  - Access management
shortTitle: Chaves de implantação
---

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
{% ifversion fpt or ghec or ghes > 3.4 or ghae-issue-5658 %}
3. In the "Security" section of the sidebar, click **{% octicon "key" aria-label="The key icon" %} Deploy keys**.
{% else %}
3. Na barra lateral esquerda, clique em **Deploy keys** (Chaves de implantação). ![Configuração das chaves de implantação](/assets/images/help/settings/settings-sidebar-deploy-keys.png)
{% endif %}
4. Na página das chaves de implantação, anote as chaves de implantação associadas à sua conta. Para as chaves não reconhecidas ou desatualizadas, clique em **Delete** (Excluir). Se houver chaves de implantação válidas que deseja manter, clique em **Approve** (Aprovar). ![Lista de chaves de implantação](/assets/images/help/settings/settings-deploy-key-review.png)

Para obter mais informações, consulte "[Gerenciar chaves de implantação](/guides/managing-deploy-keys)".

## Leia mais
- [Configurar notificações](/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/configuring-notifications#organization-alerts-notification-options)

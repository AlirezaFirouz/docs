---
title: Adicionar gerentes do aplicativo GitHub em sua organização
intro: Os proprietários da organização podem conceder aos usuários a capacidade de gerenciar alguns ou todos os {% data variables.product.prodname_github_apps %} pertencentes à organização.
redirect_from:
- /articles/adding-github-app-managers-in-your-organization
- /github/setting-up-and-managing-organizations-and-teams/adding-github-app-managers-in-your-organization
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
- Organizations
- Teams
shortTitle: Add GitHub App managers
ms.openlocfilehash: d8389c85c847b750bdb83eb8b922ad16bfa33bf3
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: "145126481"
---
Para obter mais informações sobre as permissões de gerente do {% data variables.product.prodname_github_app %}, confira "[Funções em uma organização](/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization#github-app-managers)".

## Dar a alguém a capacidade de gerenciar todos os {% data variables.product.prodname_github_apps %} pertencentes à organização

{% data reusables.profile.access_org %} {% data reusables.profile.org_settings %} {% data reusables.organizations.github-apps-settings-sidebar %}
1. Em "Gerenciamento", digite o nome de usuário da pessoa que deseja designar como um gerente do {% data variables.product.prodname_github_app %} na organização e clique em **Conceder**.
![Adicionar um gerente do {% data variables.product.prodname_github_app %}](/assets/images/help/organizations/add-github-app-manager.png)

## Dar a um indivíduo a capacidade de gerenciar um {% data variables.product.prodname_github_app %} individual

{% data reusables.profile.access_org %} {% data reusables.profile.org_settings %} {% data reusables.organizations.github-apps-settings-sidebar %}
1. Em "{% data variables.product.prodname_github_apps %}", clique no avatar do aplicativo ao qual você deseja adicionar um gerente de {% data variables.product.prodname_github_app %}.
![Seleção do {% data variables.product.prodname_github_app %}](/assets/images/help/organizations/select-github-app.png) {% data reusables.organizations.app-managers-settings-sidebar %}
1. Em "Gerentes de aplicativo", digite o nome de usuário da pessoa que deseja designar como gerente do Aplicativo do GitHub para o aplicativo e clique em **Conceder**.
![Adicionar um gerente do {% data variables.product.prodname_github_app %} a um aplicativo específico](/assets/images/help/organizations/add-github-app-manager-for-app.png)

{% ifversion fpt or ghec %}
## Leitura adicional

- "[Sobre o {% data variables.product.prodname_dotcom %} Marketplace](/articles/about-github-marketplace/)" {% endif %}

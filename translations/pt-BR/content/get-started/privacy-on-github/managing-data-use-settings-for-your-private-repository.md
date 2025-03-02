---
title: Gerenciando configurações de uso de dados para seu repositório privado
intro: 'Para ajudar o {% data variables.product.product_name %} a conectar você a ferramentas, pessoas, projetos e informações relevantes, você pode configurar o uso de dados de seu repositório privado.'
redirect_from:
  - /articles/opting-into-or-out-of-data-use-for-your-private-repository
  - /github/understanding-how-github-uses-and-protects-your-data/opting-into-or-out-of-data-use-for-your-private-repository
  - /github/understanding-how-github-uses-and-protects-your-data/managing-data-use-settings-for-your-private-repository
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Policy
  - Legal
shortTitle: Gerenciar o uso de dados para repositório privado
---

## Sobre o uso de dados para seu repositório privado

Ao habilitar o uso de dados para seu repositório privado, poderá acessar o gráfico de dependências, em que você pode acompanhar as dependências do repositório e receber {% data variables.product.prodname_dependabot_alerts %} quando o {% data variables.product.product_name %} detectar dependências vulneráveis. Para obter mais informações, consulte "[Sobre {% data variables.product.prodname_dependabot_alerts %}](/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies#dependabot-alerts-for-vulnerable-dependencies)".

## Habilitar ou desabilitar os recursos de uso de dados

{% data reusables.security.security-and-analysis-features-enable-read-only %}

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
{% data reusables.repositories.navigate-to-security-and-analysis %}
4. Em "Segurança e análise de código", à direita do recurso, clique em **Desabilitar** ou **Habilitar**.{% ifversion fpt %} !["Enable" or "Disable" button for "Configure security and analysis" features](/assets/images/help/repository/security-and-analysis-disable-or-enable-fpt-private.png){% elsif ghec %}
!["Enable" or "Disable" button for "Configure security and analysis" features](/assets/images/help/repository/security-and-analysis-disable-or-enable-ghec-private.png){% endif %}

## Leia mais

- "[Sobre o uso de seus dados pelo {% data variables.product.prodname_dotcom %}](/articles/about-github-s-use-of-your-data)"
- "[Visualizando {% data variables.product.prodname_dependabot_alerts %} para dependências vulneráveis](/github/managing-security-vulnerabilities/viewing-and-updating-vulnerable-dependencies-in-your-repository)"
- "[Gerenciar as configurações de segurança e análise para o seu repositório](/github/administering-a-repository/managing-security-and-analysis-settings-for-your-repository)"

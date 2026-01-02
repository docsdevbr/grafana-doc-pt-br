---
# Copyright (c) 2026 Grafana Labs.
# Grafana and the Grafana logo are trademarks owned by Raintank, Inc. dba
# Grafana Labs.
#
# Documentation licensed under the GNU Affero General Public License Version 3.
# For license exceptions, see LICENSING.md.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/grafana/grafana/blob/-/LICENSE
# https://github.com/grafana/grafana/blob/-/LICENSING.md

source_url: https://github.com/grafana/grafana/blob/main/docs/sources/_index.md
revision: f43d39f8ad8aec6139fbcda7e8a54741f949064b
status: ready

aliases:
  - /docs/grafana/v1.1/
  - /docs/grafana/v3.1/
  - guides/reference/admin/
cascade:
  LOKI_VERSION: latest
  TEMPO_VERSION: latest
  ONCALL_VERSION: latest
  PYROSCOPE_VERSION: latest
description: |-
  Encontre respostas para suas perguntas técnicas e saiba como usar os produtos
  Grafana OSS e Enterprise.
keywords:
  - grafana
  - começando
  - primeiros passos
  - documentação
labels:
  products:
    - enterprise
    - oss
menuTitle: Documentação do Grafana
title: Grafana OSS and Enterprise
hero:
  title: Grafana OSS e Enterprise
  level: 1
  width: 100
  image: /media/docs/grafana-cloud/infrastructure/grafanalogo.svg
  height: 100
  description: |-
    Consulte, visualize, alerte e explore suas métricas, logs e traces onde quer
    que estejam armazenados.
cards:
  title_class: pt-0 lh-1
  items:
    - title: Novidades
      href: ./whatsnew/
      description: |-
        Navegue pelos destaques de lançamentos, descontinuações e alterações
        significativas nas versões do Grafana.
      height: 24
    - title: Introdução
      href: ./fundamentals/
      description: |-
        Aprenda sobre tópicos de observabilidade em geral e alguns dos produtos
        incluídos no Grafana.
      height: 24
    - title: Configuração
      href: ./setup-grafana/
      description: Comece a usar o Grafana.
      height: 24
    - title: Fontes de dados
      href: ./datasources/
      description: |-
        Gerencie fontes de dados e saiba como configurar ou consultar as fontes
        de dados integradas.
      height: 24
    - title: Dashboards
      href: ./dashboards/
      description: |-
        Consulte, transforme, visualize e entenda seus dados, independentemente
        de onde estejam armazenados.
      height: 24
    - title: Painéis e visualizações
      href: ./panels-visualizations/
      description: |-
        Colete, correlacione e visualize dados facilmente para tomar decisões
        informadas em tempo real.
      height: 24
    - title: Explore
      href: ./explore/
      description: |-
        Explore seus dados usando uma consulta em vez de criar um dashboard.
      height: 24
    - title: Alertas
      href: ./alerting/
      description: |-
        Aprenda sobre problemas em seus sistemas momentos após eles ocorrerem.
      height: 24
    - title: Administração
      href: ./administration/
      description: |-
        Execute tarefas administrativas, como configurar o gerenciamento de
        pessoas usuárias, funções e permissões.
      height: 24
    - title: Solução de problemas
      href: ./troubleshooting/
      description: Solucione problemas comuns do Grafana.
      height: 24
    - title: Atualização
      href: ./upgrade-guide/
      description: |-
        Atualize o Grafana para se manter atualizado com as últimas correções e
        melhorias.
      height: 24
---

{{< docs/hero-simple key="hero" >}}

---

## Visão geral

O _Grafana Open Source Software (OSS)_ permite consultar, visualizar, emitir
alertas e explorar suas métricas, logs e traces onde quer que estejam
armazenados.
Os plugins de fonte de dados do Grafana permitem consultar fontes de dados,
incluindo bancos de dados de séries temporais como Prometheus e CloudWatch,
ferramentas de log como Loki e Elasticsearch, bancos de dados NoSQL/SQL como
Postgres, ferramentas de CI/CD como GitHub e muito mais.
O Grafana OSS fornece ferramentas para exibir esses dados em dashboards
dinâmicos com gráficos e visualizações intuitivos.

O _Grafana Enterprise_ é uma edição comercial do Grafana que inclui plugins
exclusivos de fonte de dados e recursos adicionais não encontrados na versão de
código aberto.
Você também recebe suporte e treinamento 24x7x365 da equipe principal do
Grafana.
Para saber mais sobre esses recursos, consulte
[Recursos corporativos](https://grafana.com/docs/grafana/<GRAFANA_VERSION>/introduction/grafana-enterprise/#enterprise-features-in-grafana-cloud).

## Orientação e ajuda

{{< guide
  name="whichgrafana"
  title="Qual Grafana é ideal para você?"
  text="Responda a algumas perguntas e o Grot ajudará você a decidir." >}}

## Aprenda

{{< card-grid key="cards" type="simple" >}}

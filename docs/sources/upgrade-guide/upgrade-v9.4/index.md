---
# Copyright (c) 2025 Grafana Labs.
# Grafana and the Grafana logo are trademarks owned by Raintank, Inc. dba
# Grafana Labs.

# Documentation licensed under the GNU Affero General Public License.
# For license exceptions, see LICENSING.md.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/grafana/grafana/blob/main/LICENSE
# https://github.com/grafana/grafana/blob/main/LICENSING.md

description: Upgrade to Grafana v9.4
keywords:
  - grafana
  - configuration
  - documentation
  - upgrade
labels:
  products:
    - enterprise
    - oss
menutitle: Upgrade to v9.4
title: Upgrade to Grafana v9.4
weight: 1995
---

# Upgrade to Grafana v9.4

{{< docs/shared lookup="upgrade/intro.md" source="grafana" version="<GRAFANA VERSION>" >}}

{{< docs/shared lookup="back-up/back-up-grafana.md" source="grafana" version="<GRAFANA VERSION>" leveloffset="+1" >}}

{{< docs/shared lookup="upgrade/upgrade-common-tasks.md" source="grafana" version="<GRAFANA VERSION>" >}}

## Technical notes

The upgrade to Grafana v9.4 includes changes to the Grafana database for Grafana alerting that are not backward compatible. As a result, when you upgrade to Grafana v9.4, do not downgrade your Grafana instance to an earlier version. Doing so might cause issues with managing your Grafana alerts.

---
# Copyright (c) 2025 Grafana Labs.
# Grafana and the Grafana logo are trademarks owned by Raintank, Inc. dba
# Grafana Labs.

# Documentation licensed under the GNU Affero General Public License.
# For license exceptions, see LICENSING.md.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/grafana/grafana/blob/main/LICENSE
# https://github.com/grafana/grafana/blob/main/LICENSING.md

title: Configure traces to profiles
menuTitle: Configure traces to profiles
description: Learn how to configure the traces to profiles integration in Grafana and Grafana Cloud.
weight: 300
keywords:
  - continuous profiling
  - tracing
---

# Configure traces to profiles

{{< admonition type="note" >}}

Your application must be instrumented for profiles and traces. For more information, refer to [Link traces to profiles](https://grafana.com/docs/pyroscope/<PYROSCOPE_VERSION>/configure-client/trace-span-profiles/).

{{< /admonition >}}

[//]: # 'Shared content for Trace to profiles in the Tempo data source'

{{< docs/shared source="grafana" lookup="datasources/tempo-traces-to-profiles.md" version="<GRAFANA VERSION>" >}}

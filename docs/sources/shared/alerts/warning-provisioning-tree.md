---
# Copyright (c) 2025 Grafana Labs.
# Grafana and the Grafana logo are trademarks owned by Raintank, Inc. dba
# Grafana Labs.

# Documentation licensed under the GNU Affero General Public License.
# For license exceptions, see LICENSING.md.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/grafana/grafana/blob/main/LICENSE
# https://github.com/grafana/grafana/blob/main/LICENSING.md

title: 'Warning Provisioning Tree'
---

{{< admonition type="warning" >}}

Since the policy tree is a single resource, provisioning it will overwrite all policies in the notification policy tree. However, it does not affect internal policies created when alert rules directly select a contact point.

{{< /admonition >}}

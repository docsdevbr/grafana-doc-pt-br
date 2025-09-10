---
# Copyright (c) 2025 Grafana Labs.
# Grafana and the Grafana logo are trademarks owned by Raintank, Inc. dba
# Grafana Labs.

# Documentation licensed under the GNU Affero General Public License.
# For license exceptions, see LICENSING.md.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/grafana/grafana/blob/main/LICENSE
# https://github.com/grafana/grafana/blob/main/LICENSING.md

labels:
  products:
    - oss
title: 'Math example'
---

- `$A` returns series `{host="web01"} 30` and `{host="web02"} 20`.
- `$B` returns series `{host="web01"} 10` and `{host="web02"} 0`.
- `$A + $B` returns `{host="web01"} 40` and `{host="web02"} 20`.

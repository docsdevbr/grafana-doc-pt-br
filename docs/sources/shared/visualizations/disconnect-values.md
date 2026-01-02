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

title: Disconnect values
---

### Disconnect values

Choose whether to set a threshold above which values in the data should be disconnected.

- **Never** - Time series data points in the data are never disconnected.
- **Threshold** - Specify a threshold above which values in the data are disconnected. This can be useful when desired values in the data are of a known size and/or within a known range, and values outside this range should no longer be connected.

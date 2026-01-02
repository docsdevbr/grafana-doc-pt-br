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

title: 'Alerting Produces '
---

#### Produces

- `application/json`
- `application/yaml`
- `application/terraform+hcl`
- `text/yaml`
- `text/hcl`

These outputs are for [file provisioning](https://grafana.com/docs/grafana/<GRAFANA_VERSION>/alerting/set-up/provision-alerting-resources/file-provisioning) or [Terraform provisioning](https://grafana.com/docs/grafana/<GRAFANA_VERSION>/alerting/set-up/provision-alerting-resources/file-provisioning), and they-including the JSON output—cannot be used to update resources via the HTTP API.

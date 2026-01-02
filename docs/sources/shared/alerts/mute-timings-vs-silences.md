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

labels:
  products:
    - oss
title: 'Mute timings vs silences'
---

## Mute timings vs silences

[Mute timings](ref:shared-mute-timings) and [silences](ref:shared-silences) are distinct methods to suppress notifications. They do not prevent alert rules from being evaluated or stop alert instances from appearing in the user interface; they only prevent notifications from being created.

The following table highlights the key differences between mute timings and silences.

|            | Mute timing                                                 | Silence                                                          |
| ---------- | ----------------------------------------------------------- | ---------------------------------------------------------------- |
| **Setup**  | Created and then added to notification policies             | Matches alerts using labels to determine whether to silence them |
| **Period** | Uses time interval definitions that can repeat periodically | Has a fixed start and end time                                   |

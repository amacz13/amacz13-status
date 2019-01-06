+++
# default attributes for an incident.
#
title = "Installation"
date = "2019-01-06"

# severity: represents the impact of
# your system due to the current incident.
# This is the list of supported severities:
#
# - under-maintenance
# - degraded-performance
# - partial-outage
# - major-outage
#
severity = "major-outage"

# affectedsystems: is a list of systems affected
# by the incident.
# Example:
# affectedsystems = ["API", "CDN"]
#
affectedsystems = ["Serveur Secondaire"]

# resolved: marks an incident as resolved.
# It can be either true or false.
#
resolved = false
+++

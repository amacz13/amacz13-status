+++
# default attributes for an incident.
#
title = "Maintenance du site web"
date = 2019-01-03 22:45

# severity: represents the impact of
# your system due to the current incident.
# This is the list of supported severities:
#
# - under-maintenance
# - degraded-performance
# - partial-outage
# - major-outage
#
severity = "under-maintenance"

# affectedsystems: is a list of systems affected
# by the incident.
# Example:
# affectedsystems = ["API", "CDN"]
#
affectedsystems = ["API", "CDN"]

# resolved: marks an incident as resolved.
# It can be either true or false.
#
resolved = false
+++

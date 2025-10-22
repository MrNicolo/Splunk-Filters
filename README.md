# Splunk-Filters

- index=zeek_conn
| stats count by src
| sort ~count
| head

index=* | stats count by index

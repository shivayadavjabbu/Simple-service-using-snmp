# Simple-service-using-snmp
This is a script to probe an SNMP agent and find the rate of change for several OIDs between successive probes/samples. The rate calculated for each OID should be displays on the console, one line for each probe instance, the output format will be described in detail in 'output format'. The solution handles COUNTER32, COUNTER64, GAUGE, and OCTET_STR.

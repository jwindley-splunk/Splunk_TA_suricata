# Splunk TA for Suricata (updated)

Revamped version of the Splunk TA for Suricata, focussed on CIM compliance.

* Author: Jamie Windley
* Acknowledgements to Anthony Tellez who created the initial TA. One of his lookups has been reused
* Sourcetypes: suricata:http, suricata:dns, suricata:tls, suricata:flow, suricata:netflow, suricata:dhcp, suricata:alert


## Features

* Automatic sourcetyping
* Datamodel mapping for:
  * Certificates
  * Intrusion Detection
  * Network Resolution
  * Network Sessions
  * Network Traffic
  * Web

## Setup and Deploy

* Configure Suricata to log in eve JSON output
* Deploy add-on to a Universal Forwarder monitoring the eve.json files
   * change create an inputs.conf based on inputs.conf.example template
* Deploy add-on to Search and Indexing layer


## Contributing

Please contribute with any updates or improvements as necessary.

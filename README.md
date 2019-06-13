## SolrPasswordHash
Standalone Java application for generating hashes for Solr basic authentication.
Simple command line tool to generate a password hash for `security.json`

Ref: https://www.planetcobalt.net/sdb/solr_password_hash.shtml 

### Dependency

    # Linux
    > sudo apt-get update
    > sudo apt-get install ant

### Build

    # Clone this project
    > cd SolrPasswordHash
    > ant

OR Use precompiled jar  

### Usage:

    > java -jar SolrPasswordHash.jar SomePassword
    Ac769FddHl6pOtpooYr0ZR36awybwQOZm2FNGFXZuBU= PcDTw9gQd61w4N7a6hGb4qspyruAdx3SfnSHMFoTtRs=
    
    Example usage:
    "credentials":{"myUser":"Ac769FddHl6pOtpooYr0ZR36awybwQOZm2FNGFXZuBU= PcDTw9gQd61w4N7a6hGb4qspyruAdx3SfnSHMFoTtRs="}
    
# License
Licensed under the Apache License v2.0

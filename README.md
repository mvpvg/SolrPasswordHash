## SolrPasswordHash
Standalone Java application for generating hashes for Solr basic authentication.
Simple command line tool to generate a password hash for `security.json`

Ref: https://www.planetcobalt.net/sdb/solr_password_hash.shtml 

### Build

    cd SolrPasswordHash
    ant

### Usage:

    java -jar SolrPasswordHash.jar SomePassword
    HZtl83vopLyZfOpGedEQveAwvVdAQ1Ukr6dDJPEfs/w= MTIz
    Example usage:
    "credentials":{"myUser":"HZtl83vopLyZfOpGedEQveAwvVdAQ1Ukr6dDJPEfs/w= MTIz"}
    
# License
Licensed under the Apache License v2.0

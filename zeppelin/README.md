# For SOLR interpreter in Zeppelin use the following properties
`default.driver` : `org.apache.solr.client.solrj.io.sql.DriverImpl`  
`default.url` : `jdbc:solr://35.171.227.8:2181/infra-solr?collection=ranger_audits`  
`default.user`: `solr`  

# in the artificat section, add the Solr jar
`org.apache.solr:solr-solrj:7.3.1`

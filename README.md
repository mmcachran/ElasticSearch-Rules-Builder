# Moved to:
https://github.com/mmcachran/ElasticPress/tree/feature/rules-builder

# ElasticPress Rules Builder
Rules builder for controlling search results. Control (boost, bury, hide) search results based on seach keywords.

## Requirements
* Elasticsearch > 5.1
* ElasticPress (https://wordpress.org/plugins/elasticpress/)
* Optional for better boost/bury logic: Enable inline scripting with the following in Elasticsearch configuration. If Elasticsearch is installed via Homebrew, the configuration file is likely in:

/usr/local/etc/elasticsearch/elasticsearch.yml

``` bash
# Enable dynamic scripting.
script.allowed_types: inline
script.allowed_contexts: search
```

## Example Simple Rule
![Simple Rule Example](readme/assets/img/ep-rules-builder-simple-rule-2.gif)

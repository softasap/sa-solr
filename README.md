sa-solr
=======

[![Build Status](https://travis-ci.org/softasap/sa-solr.svg?branch=master)](https://travis-ci.org/softasap/sa-solr)

Usage:

Simple:

```

  roles:
     - {
         role: "sa-solr",
         option_install_java: true
       }


```

Full:

```

  roles:
     - {
         role: "sa-solr",
         option_install_java: true,
         java_version: 8,
         solr_version: 6.2.0,

         solr_files_path: /var/solr,
         solr_install_path: /opt,
         solr_port: 8983,
         solr_service: solr,
         solr_user: solr
         
       }


```


see box-example for standalone deployment demo


Upon deploy SOLR will be available at http://TARGETHOST:8983/solr/#/

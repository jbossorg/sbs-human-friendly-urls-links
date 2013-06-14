Human Friendly URLs plugin extension - HF links
===============================================

Extension that overrides functionality of Struts2 URL tag component and use implementation of spring managed bean with customized implementation.
By default it tries to get the bean defined in [Jive SBS Plugin: Human Friendly URLs](https://github.com/jbossorg/sbs-human-friendly-urls)

Installation steps
------------------

1. Build module by mvn package
2. Copy target/classes/org/apache/struts2/views/freemarker/tags/URLModel.class (or take it from jar file)
   to /usr/local/jive/applications/sbs/application/WEB-INF/classes/org/apache/struts2/views/freemarker/tags/.
   Note: directory structure needs to be created before
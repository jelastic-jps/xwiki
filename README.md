[![XWiki](../../raw/master/images/xwiki_logo.png)](../../../xwiki)
## XWiki

The JPS package deploys XWiki that initially contains 1 application server and 1 database container.

### Highlights
This package is designed to deploy XWiki environment which represents a professional wiki.<br />That has powerful extensibility features such as scripting in pages, plugins and a highly modular architecture.

### Specifics

Layer                |     Server    | Number of CTs <br/> by default | Cloudlets per CT <br/> (reserved/dynamic) | Options
-------------------- | --------------| :----------------------------: | :---------------------------------------: | :-----:
AS                   |   Tomcat 9    |       1                        |           4 / 16                          | -
DB                   |  MariaDB 10   |       1                        |           1 / 8                           | -

* AS - Application server 
* DB - Database 
* CT - Container

**XWiki Version**: Stable 13.2 <br/>
**Tomcat Version**: 9.x <br/>
**Java Engine**: Java 8 <br/>
**MariaDB Database**: 10.x

### Deployment

In order to get this solution instantly deployed, click the "Get It Hosted Now" button, specify your email address within the widget, choose one of the [Jelastic Public Cloud providers](https://jelastic.cloud) and press Install.

[![GET IT HOSTED](https://raw.githubusercontent.com/jelastic-jps/jpswiki/master/images/getithosted.png)](https://jelastic.com/install-application/?manifest=https%3A%2F%2Fgithub.com%2Fjelastic-jps%2Fxwiki%2Fraw%2Fmaster%2Fmanifest.jps)

To deploy this package to Jelastic Private Cloud, import [this JPS manifest](../../raw/master/manifest.jps) within your dashboard ([detailed instruction](https://docs.jelastic.com/environment-export-import#import)).

More information about Jelastic JPS package and about installation widget for your website can be found in the [Jelastic JPS Application Package](https://github.com/jelastic-jps/jpswiki/wiki/Jelastic-JPS-Application-Package) reference.

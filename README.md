# Drupal documentation

## Infrastructure

### [Composer repository](https://github.com/City-of-Helsinki/drupal-repository)

A custom Composer repository used to distribute dependencies as part of [City-of-Helsinki/drupal-helfi-platform](https://github.com/City-of-Helsinki/drupal-helfi-platform) ecosystem.

Provides a bunch of webhooks used to automate various things. See [Documentation](https://github.com/City-of-Helsinki/drupal-repository) for more information.

### [Docker images](https://github.com/City-of-Helsinki/drupal-docker-images)

Contains documentation and build scripts for Docker images used by City-of-Helsinki Drupal projects.

### [Local proxy](https://github.com/City-of-Helsinki/drupal-helfi-local-proxy)

A proxy to serve all local projects through one domain (`helfi-proxy.docker.so`). This can be used to replicate production like setup on local environment.

### [TPR Aggregator](https://github.com/City-of-Helsinki/drupal-tpr-aggregator)

Aggregates TPR<sup>[[1]](https://www.hel.fi/palvelukarttaws/restpages/ver4_en.html)</sup><sup>[[2]](https://www.hel.fi/palvelukarttaws/restpages/palvelurekisteri_en.html)</sup> data to make it easier/faster to be processed by [City-of-Helsinki/drupal-module-helfi-tpr](https://github.com/City-of-Helsinki/drupal-module-helfi-tpr) migrations.

## Modules

### [API base](https://github.com/City-of-Helsinki/drupal-module-helfi-api-base)

A base module for [City-of-Helsinki/drupal-helfi-platform](https://github.com/City-of-Helsinki/drupal-helfi-platform) ecosystem. Contains various features used in other custom modules.

### [Azure Filesystem](https://github.com/City-of-Helsinki/drupal-module-helfi-azure-fs)

Provides various fixes to deal with Azure's NFS mount and an integration to Azure's Blob storage service using [flysystem](https://www.drupal.org/project/flysystem) and [flysystem_azure](https://www.drupal.org/project/flysystem_azure) modules.

### [Navigation](https://github.com/City-of-Helsinki/drupal-module-helfi-navigation)

Navigation module allows aggregation of instance specific main-navigations and sharing menus between Helfi-instances. The master repository for all menus is [Etusivu](https://github.com/City-of-Helsinki/drupal-helfi-etusivu)-instance

### [Platform config](https://github.com/City-of-Helsinki/drupal-helfi-platform-config)

Provides shared Drupal configurations used by [City-of-Helsinki/drupal-helfi-platform](https://github.com/City-of-Helsinki/drupal-helfi-platform) projects.

### [Proxy](https://github.com/City-of-Helsinki/drupal-module-helfi-proxy)

Provides various fixes to allow multiple Drupal instances to be served from one domain.

### [TPR Integration](https://github.com/City-of-Helsinki/drupal-module-helfi-tpr)

Integrates [Helsinki Service Map](https://www.hel.fi/palvelukarttaws/restpages/ver4_en.html) and [TPR Service Description Register](https://www.hel.fi/palvelukarttaws/restpages/palvelurekisteri_en.html) with Drupal.

### [Tunnistamo integration](https://github.com/City-of-Helsinki/drupal-module-helfi-tunnistamo)

Provides an integration to [City-of-Helsinki/tunnistamo](https://github.com/City-of-Helsinki/tunnistamo) OpenID Connect (OIDC) service.

## Projects

See https://helsinkisolutionoffice.atlassian.net/wiki/spaces/HEL/pages/7710015550/Instanssit+ja+repositoryt

### [Asuminen](https://github.com/City-of-Helsinki/drupal-helfi-asuminen)

`@todo` fill short description

### [Etusivu](https://github.com/City-of-Helsinki/drupal-helfi-etusivu)

Etusivu is the front page of the hel.fi project, featuring elements like the global menu, news, and articles, which are also used on other pages. Additionally, Etusivu offers alternative language options not available on other instances.

### [Työ ja yrittäminen](https://github.com/City-of-Helsinki/drupal-helfi-tyo-yrittaminen)

ELO (Yritykset ja työ, formerly known as Työ ja yrittäminen) covers topics related to work and entrepreneurship.

### [Kasvatus ja koulutus](https://github.com/City-of-Helsinki/drupal-helfi-kasvatus-koulutus)

KASKO, short for kasvatus ja koulutus, is the site for the department responsible for childhood and education in the city of Helsinki. The site includes multiple unit searches and a bit complex system built using the Group contrib module for upper secondary schools. Additionally, this  instance has the News feature enabled and used for upper secondary schools.

### [Kulttuuri ja vapaa-aika / KuVA](https://github.com/City-of-Helsinki/drupal-helfi-kuva)

`@todo` fill short description

### [Kaupunkiympäristö ja liikenne / KYMP](https://github.com/City-of-Helsinki/drupal-helfi-kymp)

`@todo` fill short description

### [Avoimet tyopaikat / Rekry](https://github.com/City-of-Helsinki/drupal-helfi-rekry)

Avoimet työpaikat, also called Rekry, is a site integrated with Helbit. It migrates job listings to the job search found on the site and provides other recruitment information for the city of Helsinki.

### [Sosiaali ja terveyspalvelut / SOTE](https://github.com/City-of-Helsinki/drupal-helfi-sote)

`@todo` fill short description

### [Päätöksenteko ja hallinto / STRATEGIA](https://github.com/City-of-Helsinki/drupal-helfi-strategia)

`@todo` fill short description

### [Demo project](https://github.com/City-of-Helsinki/drupal-helfi-platform-test)

A project to test /showcase new Drupal platform features.

## Themes

### [Helsinki Drupal Base Theme / HDBT](https://github.com/City-of-Helsinki/drupal-hdbt)

HDBT theme is a base theme for the City of Helsinki. It is based on the core theme stable9. The abbrevation comes from
the words Helsinki Drupal Base Theme. Style follows the [BEM methodology](http://getbem.com/) and javascript is written
as ES6. The JS and SCSS files are compiled and minified with webpack.

### [Helsinki Drupal Base Theme - Admin / HDBT Admin](https://github.com/City-of-Helsinki/drupal-hdbt-admin)

HDBT Admin theme is an admin theme for the City of Helsinki. It is based on the contrib theme called Gin. The abbrevation comes from
the words Helsinki Drupal Base Theme. Style follows the [BEM methodology](http://getbem.com/) and javascript is written
as ES6. The JS and SCSS files are compiled and minified with webpack.

## Testing

### [Robot-framework tests](https://github.com/City-of-Helsinki/helfi-test-automation-python)

NOTICE: Currently this part of the project is unusable since it has a dependency to helfi_example_content module that is no longer available.
Automated tests done using Robot-framework. The readme has framework installation and running instructions.

## Tools

### [Drupal tools](https://github.com/City-of-Helsinki/drupal-tools)

Provides Drush commands to perform various tasks.

### [Druidfi tools](https://github.com/druidfi/tools)

Set of tools meant for ease the development.

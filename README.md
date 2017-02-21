# LDAP and Postgres-Enhanced MediaWiki

This wiki is designed to work as an internal, general purpose wiki with LDAP/Active Directory Authentication enabled. It's based on [kristophjunge/mediawiki](https://hub.docker.com/r/kristophjunge/mediawiki/), adding some features: 

 - [LDAP](https://www.mediawiki.org/wiki/Extension:LDAP_Authentication)
 - [ExternalData](https://www.mediawiki.org/wiki/Extension:ExternalData) (including the drivers needed for Posgres)

# How to use this image

The guidance on this image is intentionally short. Please refer to the good documentation for  [kristophjunge/mediawiki](https://hub.docker.com/r/kristophjunge/mediawiki/).
## Docker Compose

I recommend you use [Docker Compose](https://docs.docker.com/compose/) to manage this service. It will start all the dependent services quickly. To get started, simply copy the files provided in the [example](example/) directory in this repository, configure it as you'd like and run:

    docker-compose up


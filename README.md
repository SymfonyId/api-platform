Dunglas's API platform
=======================

Welcome to Dunglas's API platform - a fully-functional Symfony2
application that you can use as the skeleton to build a hypermedia
and auto-discoverable REST API relying on internet standards.

It provides [JSON-LD][1] and [Hydra][2] support out of the box.

Install
-------

Use [Composer][3] to create your new project:

    composer create-project dunglas/api-platform my-api

Start to hack
-------------

A default application representing a bookstore is installed by default.

Run `bin/console server:start` and open `http://localhost:8000` in any
HTTP client to play it.
Give a try to [HydraConsole][4] to leverage JSON-LD and Hydra features.

What's inside?
--------------

Dunglas's API platform provides rock solid fundations to build your API:

  * The full power of the [**Symfony**][5] framework and its ecosystem;

  * **[Doctrine][6] ORM/DBAL**;

  * [**PHP Schema**][7] to generate Doctrine entities (with Symfony
    validation and extended PHPDoc) from [Schema.org][8] types.

  * [**DunglasJsonLdApiBundle**][9] to expose in minutes your entities as
    a JSON-LD and Hydra enabled hypermedia REST API.

  * [Behat][10] and [Behatch][11] configured to easily test the API.

  * An AppBundle you can use to start coding;

  * Annotations enabled for everything;

  * Swiftmailer and Twig to create beautiful emails;

It comes pre-configured with the following bundles:

  * [**Symfony**][5] - Dunglas's API platform is built on top of the
    full-stack Symfony framework

  * [**DunglasJsonLdApiBundle**][9] - Creates powerful Hypermedia APIs
    supporting JSON-LD and Hydra

  * [**NelmioCorsBundle**][12] - Support for CORS headers

  * [**FosHttpCacheBundle**][13] - Add powerful caching capacities, supports
    Varnish, Nginx a built-in PHP reverse proxy

  * [**SensioFrameworkExtraBundle**][14] - Adds several enhancements, including
    template and routing annotation capability

  * [**DoctrineBundle**][15] - Adds support for the Doctrine ORM

  * [**TwigBundle**][16] - Adds support for the Twig templating engine

  * [**SecurityBundle**][17] - Adds security by integrating Symfony's security
    component

  * [**SwiftmailerBundle**][18] - Adds support for Swiftmailer, a library for
    sending emails

  * [**MonologBundle**][19] - Adds support for Monolog, a logging library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**][20] (in dev/test env) - Adds code generation
    capabilities

All libraries and bundles included in Dunglas's API platform are
released under the MIT or BSD license.


Authentication support
----------------------

Json Web Token is a lightweight and popular way to handle authentication in a
stateless way. Install [**LexikJWTAuthenticationBundle**][21] to adds JWT support
to Dunglas's API platform.

Oauth support can also be easily added using [**FOSOAuthServerBundle**][22].

Enjoy!

Credits
-------

Built by [Kévin Dunglas][23].

[1]:  http://json-ld.org
[2]:  http://hydra-cg.com
[3]:  http://getcomposer.org
[4]:  http://www.markus-lanthaler.com/hydra/
[5]:  http://symfony.com
[6]:  http://doctrine-project.org
[7]:  http://php-schema.dunglas.com
[9]:  http://schema.org
[9]:  https://github.com/dunglas/DunglasJsonLdApiBundle
[10]: http://behat.readthedocs.org
[11]: https://github.com/Behatch/contexts
[12]: https://github.com/nelmio/NelmioCorsBundle
[13]: http://foshttpcachebundle.readthedocs.org
[14]: http://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/index.html
[15]: http://symfony.com/doc/current/book/doctrine.html
[16]: http://symfony.com/doc/current/book/templating.html
[17]: http://symfony.com/doc/current/book/security.html
[18]: http://symfony.com/doc/current/cookbook/email.html
[19]: http://symfony.com/doc/current/cookbook/logging/monolog.html
[20]: http://symfony.com/doc/current/bundles/SensioGeneratorBundle/index.html
[21]: https://github.com/lexik/LexikJWTAuthenticationBundle
[22]: https://github.com/FriendsOfSymfony/FOSOAuthServerBundle
[23]: http://dunglas.fr

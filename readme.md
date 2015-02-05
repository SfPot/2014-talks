# SfPot 2014 talks

### Summary

- [Applying Domain Driven Design with Symfony2 projects](#applying-domain-driven-design-with-symfony2-projects)
- [Code Agile - comment redéfinir la qualité](#code-agile---comment-redéfinir-la-qualité-french) _<sup>(french)</sup>_
- [Configuration Discovery avec Symfony2](#configuration-discovery-avec-symfony2-french) _<sup>(french)</sup>_
- [Dependency Injection Loves TDD](#dependency-injection-loves-tdd)
- [Domain Driven Design (DDD) et comment le mettre en œuvre dans une application Symfony 2](#domain-driven-design-ddd-et-comment-le-mettre-en-œuvre-dans-une-application-symfony-2-french)
- [Interopérabilité cross-frameworks](#interopérabilité-cross-frameworks-french) _<sup>(french)</sup>_
- [Integration et deploiement continu avec Travis CI](#integration-et-deploiement-continu-avec-travis-ci-french) _<sup>(french)</sup>_
- [Introduction à PHPCR](#introduction-à-phpcr-french) _<sup>(french)</sup>_
- [Introduction to Sonata](#introduction-to-sonata)
- [Le cache HTTP sous authentification avec varnish](#le-cache-http-sous-authentification-avec-varnish-french) _<sup>(french)</sup>_
- [Le concept DevOps](#le-concept-devops-french) _<sup>(french)</sup>_
- [OpenClassrooms : Design Applicatif avec Symfony2 - Zoom sur la Clean Architecture ](#openclassrooms--design-applicatif-avec-symfony2---zoom-sur-la-clean-architecture--french)
- [Optimizing Your Front End Workflow](#optimizing-your-front-end-workflow)
- [phpspec](#phpspec)
- [Présentation d'une approche de modélisation en DDD par l'exemple](#présentation-dune-approche-de-modélisation-en-ddd-par-lexemple-french) _<sup>(french)</sup>_
- [Présentation de Prophecy](#présentation-de-prophecy-french) _<sup>(french)</sup>_
- [Présentation du nouveau software Blackfire.io](#présentation-du-nouveau-software-blackfireio)
- [Protips pour Symfony2 (mais pas que)](#protips-pour-symfony2-mais-pas-que-french) _<sup>(french)</sup>_
- [Provisioning d'un projet Symfony avec Ansible](#provisioning-dun-projet-symfony-avec-ansible-french) _<sup>(french)</sup>_
- [Réaliser des applications innovantes avec Symfony2](#réaliser-des-applications-innovantes-avec-symfony2-french) _<sup>(french)</sup>_
- [Retour d'experience avec EkinoWordpressBundle sur un site à forte charge](#retour-dexperience-avec-ekinowordpressbundle-sur-un-site-à-forte-charge-french)
- [Routing Symfony et Symfony CMF](#routing-symfony-et-symfony-cmf-french) _<sup>(french)</sup>_
- [Scaling Symfony2 apps with RabbitMQ](#scaling-symfony2-apps-with-rabbitmq)
- [Silex saved me from my legacy code](#silex-saved-me-from-my-legacy-code)
- [Sonata Block Bundle](#sonata-block-bundle)
- [Speed up your Symfony2 application and build awesome features with Redis](#speed-up-your-symfony2-application-and-build-awesome-features-with-redis)
- [Symfony2 : Performances et Optimisations](#symfony2--performances-et-optimisations-french) _<sup>(french)</sup>_
- [Symfony2 Security & Websockets](#symfony2-security--websockets-french) _<sup>(french)</sup>_
- [Symfony à L'Express - Toute une histoire](#symfony-à-lexpress---toute-une-histoire-french) _<sup>(french)</sup>_
- [Utilisation de Docker dans le cadre de projets Symfony](#utilisation-de-docker-dans-le-cadre-de-projets-symfony-french) _<sup>(french)</sup>_
- [When Monolog meet ELK](#when-monolog-meet-elk)
- [Working with Events in Symfony2](#working-with-events-in-symfony2)
- [Yucca ORM](#yucca-orm)

---

## Présentation de Prophecy _<sup>(french)</sup>_

<dl>
  <dt>Description</dt>
  <dd>Présentation de Prophecy, la librairie de mock créée pour PhpSpec 2 (mais indépendante). Cette présentation ne traitera pas de PhpSpec 2 (probablement juste évoquée), mais juste Prophet: nous verrons comment l'utiliser dans nos tests PhpUnit, par exemple.</dd>
</dl>

~~Slides~~  
~~Video~~  
[Project on GitHub](https://github.com/phpspec/prophecy)

By [Christophe Coevoet](https://connect.sensiolabs.com/profile/stof)  
![github](icon/github.png) [@stof](https://github.com/stof)  
![twitter](icon/twitter.png) [@Stof70](https://twitter.com/Stof70)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/160145562/) - 21/01/2014

---

## Symfony2 Security & Websockets _<sup>(french)</sup>_

<dl>
  <dt>Description</dt>
  <dd>La technique du ticket (#sf2 #sécurité #websockets #nodeJS)</dd>
</dl>

[Slides](https://tom32i.github.io/sf2-security-websocket/)  
~~Video~~  
[Example](https://github.com/Tom32i/sf2-security-websocket)

By [Thomas Jarrand](https://connect.sensiolabs.com/profile/tom32i)  
![github](icon/github.png) [@Tom32i](https://github.com/Tom32i)  
![twitter](icon/twitter.png) [@Tom32i](https://twitter.com/Tom32i)

## Interopérabilité cross-frameworks _<sup>(french)</sup>_

<dl>
  <dt>Description</dt>
  <dd>Faire tourner Symfony et n’importe quel autre framework dans la même application grace à HttpKernelInterface et [Stack](http://stackphp.com/), démo à l’appui.</dd>
</dl>

[Slides](http://mnapoli.fr/presentations/framework-interop-fr/)  
~~Video~~

By [Matthieu Napoli](https://connect.sensiolabs.com/profile/mnapoli)  
![github](icon/github.png) [@mnapoli](https://github.com/mnapoli)  
![twitter](icon/twitter.png) [@matthieunapoli](https://twitter.com/matthieunapoli)

![meetup](icon/location.png) [Lyon, France](http://www.meetup.com/afsy-sfpot/events/160879992/) - 23/01/2014

---

## Optimizing Your Front End Workflow

<dl>
  <dt>Description</dt>
  <dd>We take great care in our back end coding workflow, optimizing, automating and abstracting as much as is possible. So why don't we do that with our front end code?

In this session, Matthew demonstrated tools to help us take our front end workflow to the next level, and hopefully optimize our load times in the process!

We looked at using Twig templates and optimizing them for the different areas of your application, integrating Bower and Gulp for managing assets and processing our front-end code to avoid repetitive tasks - looking at how that impacts the typical Symfony workflow.</dd>
</dl>

[Slides](http://slideshare.net/mdavis1982/optimising-your-front-end-workflow-with-symfony-twig-bower-and-gulp)  
~~Video~~

By [Matthew Davis](https://connect.sensiolabs.com/profile/mdavis1982)  
![github](icon/github.png) [@mdavis1982](https://github.com/mdavis1982)  
![twitter](icon/twitter.png) [@mdavis1982](https://twitter.com/mdavis1982)

![meetup](icon/location.png) [London, United Kingdom](http://www.meetup.com/symfony/events/162008152/) - 19/02/2014

---

## Introduction à PHPCR _<sup>(french)</sup>_

~~Slides~~  
~~Video~~  
[Project on GitHub](https://github.com/phpcr/phpcr)

By Daniel Leech  
![github](icon/github.png) [@dantleech](https://github.com/dantleech)  
![twitter](icon/twitter.png) [@dantleech](https://twitter.com/dantleech)

## Présentation d'une approche de modélisation en DDD par l'exemple _<sup>(french)</sup>_

~~Slides~~  
~~Video~~

By [Xavier Gorse](https://connect.sensiolabs.com/profile/xgorse)  
![github](icon/github.png) [@xgorse](https://github.com/xgorse)  
![twitter](icon/twitter.png) [@xgorse](https://twitter.com/xgorse)

![meetup](icon/location.png) [Lyon, France](http://www.meetup.com/afsy-sfpot/events/166697832/) - 11/03/2014

---

## Sonata Block Bundle

[Slides](http://slideshare.net/th0masr/sonata-block-bundle-sfpot-march-2014)  
~~Video~~  
[Project on GitHub](https://github.com/sonata-project/SonataBlockBundle)

By [Thomas Rabaix](https://connect.sensiolabs.com/profile/rande)  
![github](icon/github.png) [@rande](https://github.com/rande)  
![twitter](icon/twitter.png) [@th0masr](https://twitter.com/th0masr)

## Code Agile - comment redéfinir la qualité _<sup>(french)</sup>_

[Slides](https://speakerdeck.com/marekkalnik/code-agile-comment-redefinir-la-qualite)  
~~Video~~

By [Marek Kalnik](https://connect.sensiolabs.com/profile/marekkalnik)  
![github](icon/github.png) [@marekkalnik](https://github.com/marekkalnik)  
![twitter](icon/twitter.png) [@marekkalnik](https://twitter.com/marekkalnik)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/171642032/) - 18/03/2014

---

## Réaliser des applications innovantes avec Symfony2 _<sup>(french)</sup>_

[Slides](http://slideshare.net/coopTilleuls/compte-rendu-du-sfpot-lillois-du-20-mars-2014)  
~~Video~~

By [Kévin Dunglas](https://connect.sensiolabs.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

And [Alexandre Salomé](https://connect.sensiolabs.com/profile/alexandresalome)  
![github](icon/github.png) [@alexandresalome](https://github.com/alexandresalome)  
![twitter](icon/twitter.png) [@alexandresalome](https://twitter.com/alexandresalome)

![meetup](icon/location.png) [Lille, France](http://les-tilleuls.coop/les-tilleuls-coop-et-sensiolabs-organisent-le-premier-sfpot-lillois/) - 20/03/2014

---

## Applying Domain Driven Design with Symfony2 projects

<dl>
  <dt>Description</dt>
  <dd>When we learn Symfony2 from the documentation, it provides us with easy and convenient ways of getting the job done. Over time our projects grow and this early convenience can become an obstacle. In this session Marek focused on how to make our code less dependent on Symfony2 and more domain focused.</dd>
</dl>

[Slides](https://speakerdeck.com/super_marek/applying-domain-driven-design-with-symfony)  
~~Video~~

By [Marek Matulka](https://connect.sensiolabs.com/profile/megaloman)  
![github](icon/github.png) [@mareg](https://github.com/mareg)  
![twitter](icon/twitter.png) [@super_marek](https://twitter.com/super_marek)

![meetup](icon/location.png) [London, United Kingdom](http://www.meetup.com/symfony/events/162109492/) - 16/04/2014

---

## phpspec

[Slides](https://docs.google.com/presentation/d/1JKGZ3hF7jsdjhDJ8vbowXYLxbJHATAVtazOXrWeDxUM/edit)  
~~Video~~  
[Project on GitHub](https://github.com/phpspec/phpspec)

By [Loïc Chardonnet](https://connect.sensiolabs.com/profile/gnusat)  
![github](icon/github.png) [@gnugat](https://github.com/gnugat)  
![twitter](icon/twitter.png) [@epiloic](https://twitter.com/epiloic)

## Le cache HTTP sous authentification avec varnish _<sup>(french)</sup>_

[Slides](https://jolicode.github.io/http-cache-conf/)  
~~Video~~

By [Joël Wurtz](https://connect.sensiolabs.com/profile/brouznouf)  
![github](icon/github.png) [@joelwurtz](https://github.com/joelwurtz)  
![twitter](icon/twitter.png) [@Brouznouf](https://twitter.com/Brouznouf)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/182869812/) - 20/05/2014

---

## Working with Events in Symfony2

[Slides](https://tom32i.github.io/sfpot-events/)  
~~Video~~

By [Thomas Jarrand](https://connect.sensiolabs.com/profile/tom32i)  
![github](icon/github.png) [@Tom32i](https://github.com/Tom32i)  
![twitter](icon/twitter.png) [@Tom32i](https://twitter.com/Tom32i)  

## Configuration Discovery avec Symfony2 _<sup>(french)</sup>_

[Sources slides](https://github.com/t-geindre/slides-applaunch)  
~~Video~~

By [Mikael Randy](https://connect.sensiolabs.com/profile/mikaelrandy)  
![github](icon/github.png) [@mikaelrandy](https://github.com/mikaelrandy)  
![twitter](icon/twitter.png) [@mikaelrandy](https://twitter.com/mikaelrandy)  

And Thierry Geindre  
![github](icon/github.png) [@t-geindre](https://github.com/t-geindre)  

![meetup](icon/location.png) [Lyon, France](http://www.meetup.com/afsy-sfpot/events/181251072/) - 22/05/2014

---

## Symfony2 : Performances et Optimisations _<sup>(french)</sup>_

[Slides](http://slideshare.net/coopTilleuls/sfpot-du-12-juin-2014-symfony-performances-et-optimisations)  
~~Video~~

By [Samuel Roze](https://connect.sensiolabs.com/profile/sroze)  
![github](icon/github.png) [@sroze](https://github.com/sroze)  
![twitter](icon/twitter.png) [@samuelroze](https://twitter.com/samuelroze)

![meetup](icon/location.png) [Lille, France](http://les-tilleuls.coop/sfpot-lillois-symfony-2-optimisations-et-performances/) - 12/06/2014

---

## Silex saved me from my legacy code

<dl>
  <dt>Description</dt>
  <dd>Facing down a megalith of legacy code is never easy. It sounds like a good idea to migrate it incrementally to a new codebase, with some buzzwords like SOA, TDD and clean code thrown in there, but how do you actually do it? And with what tools?

This is the story of how a small, simple Silex application is allowing a large tech company to modernize its legacy codebase. Using Symfony's younger brother, a simple suite of REST services can be created to support incremental code modernization.</dd>
</dl>

~~Slides~~  
[Video](http://youtu.be/OJcdHGJFfLU)

By Sam Burns  
![github](icon/github.png) [@SamBurns-awin](https://github.com/SamBurns-awin)  
![twitter](icon/twitter.png) [@AgileTillIDie](https://twitter.com/AgileTillIDie)

![meetup](icon/location.png) [London, United Kingdom](http://www.meetup.com/symfony/events/162112852/) - 18/06/2014

---

## When Monolog meet ELK

<dl>
  <dt>Description</dt>
  <dd>Monolog and Elasticsearch / Logstash / Kibana</dd>
</dl>

[Slides](https://speakerdeck.com/odolbeau/when-monolog-meet-elk)  
~~Video~~

By [Olivier Dolbeau](https://connect.sensiolabs.com/profile/odolbeau)  
![github](icon/github.png) [@odolbeau](https://github.com/odolbeau)  
![twitter](icon/twitter.png) [@odolbeau](https://twitter.com/odolbeau)

## Routing Symfony et Symfony CMF _<sup>(french)</sup>_

[Slides](https://speakerdeck.com/gromnan/routing-symfony-et-symfony-cmf)  
~~Video~~

By [Jérôme Tamarelle](https://connect.sensiolabs.com/profile/gromnan)  
![github](icon/github.png) [@GromNaN](https://github.com/GromNaN)  
![twitter](icon/twitter.png) [@GromNaN](https://twitter.com/GromNaN)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/193662672/) - 15/07/2014

---

## Integration et deploiement continu avec Travis CI _<sup>(french)</sup>_

<dl>
  <dt>Description</dt>
  <dd>Présentation de Travis CI, sa configuration, et montrera différents protips et retours d'expérience.</dd>
</dl>

[Slides](http://slides.com/reynaldm/2014-08-19_continuous_integration_and_deployment_with_travis)  
~~Video~~

By [Reynald Mandel](https://connect.sensiolabs.com/profile/reynaldm)  
![github](icon/github.png) [@reynaldm](https://github.com/reynaldm)  
![twitter](icon/twitter.png) [@r_mandel](https://twitter.com/r_mandel)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/201623362/) - 19/08/2014

---

## Scaling Symfony2 apps with RabbitMQ

<dl>
  <dt>Description</dt>
  <dd>Dealing with resource-consuming tasks in PHP can affect performance or even make you lose money because of poor user experience. Fortunately there are strategies for dealing with such problems and one of these is queueing. In this session Kacper focused on what RabbitMQ is, how it works, how we can use it with PHP and integrate it with Symfony2 applications. This talk will give you an idea of where you can apply queues in your system, and then make them fly and scale!</dd>
</dl>

[Slides](http://slideshare.net/cakper/2014-0821-symfony-uk-meetup-scaling-symfony2-apps-with-rabbit-mq)  
[Video](http://youtu.be/cha92Og9M5A)

By [Kacper Gunia](https://connect.sensiolabs.com/profile/cakper)  
![github](icon/github.png) [@cakper](https://github.com/cakper)  
![twitter](icon/twitter.png) [@cakper](https://twitter.com/cakper)  

![meetup](icon/location.png) [London, United Kingdom](http://www.meetup.com/symfony/events/162112862/) - 20/08/2014

---

## Symfony à L'Express - Toute une histoire _<sup>(french)</sup>_

[Slides](http://slides.com/j0k/symfony-lexpress)  
~~Video~~

By [Jérémy Benoist](https://connect.sensiolabs.com/profile/j0k)  
![github](icon/github.png) [@j0k3r](https://github.com/j0k3r)  
![twitter](icon/twitter.png) [@j0k](https://twitter.com/j0k)

And [Jérôme Tamarelle](https://connect.sensiolabs.com/profile/gromnan)  
![github](icon/github.png) [@GromNaN](https://github.com/GromNaN)  
![twitter](icon/twitter.png) [@GromNaN](https://twitter.com/GromNaN)

## Provisioning d'un projet Symfony avec Ansible _<sup>(french)</sup>_

[Slides](http://slides.com/kosssi/provisionning-symfony-ansible)  
~~Video~~

By [Simon Constans](https://connect.sensiolabs.com/profile/kosssi)  
![github](icon/github.png) [@kosssi](https://github.com/kosssi)  
![twitter](icon/twitter.png) [@kos_si](https://twitter.com/kos_si)

## Utilisation de Docker dans le cadre de projets Symfony _<sup>(french)</sup>_

~~Slides~~  
~~Video~~

By [Joël Wurtz](https://connect.sensiolabs.com/profile/brouznouf)  
![github](icon/github.png) [@joelwurtz](https://github.com/joelwurtz)  
![twitter](icon/twitter.png) [@Brouznouf](https://twitter.com/Brouznouf)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/206368782/) - 16/08/2014

---

## Protips pour Symfony2 (mais pas que) _<sup>(french)</sup>_

[Slides](https://speakerdeck.com/pocky/protips-symfony-mais-pas-que)  
~~Video~~

By [Alexandre Balmes](https://connect.sensiolabs.com/profile/pocky)  
![github](icon/github.png) [@pocky](https://github.com/pocky)  
![twitter](icon/twitter.png) [@pockystar](https://twitter.com/pockystar)

![meetup](icon/location.png) [Lyon, France](http://www.meetup.com/afsy-sfpot/events/208208712/) - 02/09/2014

---

## Présentation du nouveau software Blackfire.io

~~Slides~~  
~~Video~~  
[Blackfire.io](https://blackfire.io)

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

![meetup](icon/location.png) [Lyon, France](http://les-tilleuls.coop/nouveau-sfpot-a-lille-conference-de-fabien-potencier/) - 11/09/2014

---

## Le concept DevOps _<sup>(french)</sup>_

[Slides](http://slideshare.net/johniw2/introduction-au-devops-40101947)  
~~Video~~

By [Jonathan Martin](https://connect.sensiolabs.com/profile/john_iw2)  
![github](icon/github.png) [@iw2](https://github.com/iw2)  
![twitter](icon/twitter.png) [@john_iw2](https://twitter.com/john_iw2)

And [Carlo Dosso](https://connect.sensiolabs.com/profile/carlo.dosso)  
![github](icon/github.png) [@cdosso](https://github.com/cdosso)  
![twitter](icon/twitter.png) [@carlodosso](https://twitter.com/carlodosso)

![meetup](icon/location.png) [Marseille, France](http://www.meetup.com/afsy-sfpot/events/207578402/) - 09/10/2014

---

## Speed up your Symfony2 application and build awesome features with Redis

<dl>
  <dt>Description</dt>
  <dd>Redis is an extremely fast data structure server that can be easily added to your existing stack and act like a Swiss army knife to help solve many problems that would be extremely difficult to workaround with the traditional RDBMS. In this session Ricard explained what Redis is, how it works, what awesome features we can build with it, and how we can use it with PHP and Symfony2 applications making them blazing fast.</dd>
</dl>

[Slides](http://slideshare.net/ricardclau/speed-up-your-symfony2-application-and-build-awesome-features-with-redis)  
[Video](http://youtu.be/2JcLJtomjuI)

By [Ricard Clau](https://connect.sensiolabs.com/profile/ricardclau)  
![github](icon/github.png) [@ricardclau](https://github.com/ricardclau)  
![twitter](icon/twitter.png) [@ricardclau](https://twitter.com/ricardclau)

![meetup](icon/location.png) [London, United Kingdom](http://www.meetup.com/symfony/events/162112902/) - 15/10/2014

---

## Yucca ORM

[Slides](https://rjanot.github.io/conf_yucca/)  
~~Video~~  
[Project on GitHub](https://github.com/yucca-php/yucca)

By [Rémi Janot](https://connect.sensiolabs.com/profile/rjanot)  
![github](icon/github.png) [@rjanot](https://github.com/rjanot)  
![twitter](icon/twitter.png) [@r_janot](https://twitter.com/r_janot)

## Introduction to Sonata

[Slides](https://thomas.rabaix.net/talks/2014/sfpot-sonata-presentation/?full#1)  
~~Video~~  
[Project on GitHub](https://github.com/sonata-project)

By [Thomas Rabaix](https://connect.sensiolabs.com/profile/rande)  
![github](icon/github.png) [@rande](https://github.com/rande)  
![twitter](icon/twitter.png) [@th0masr](https://twitter.com/th0masr)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/213324412/) - 21/10/2014

---

## Domain Driven Design (DDD) et comment le mettre en œuvre dans une application Symfony 2 _<sup>(french)</sup>_

[Slides](https://speakerdeck.com/tyx/ddd-mise-en-pratique-avec-symfony)  
~~Video~~  
[Example](https://github.com/tyx/ddd-sample-symfony)

By [Timothée Barray](https://connect.sensiolabs.com/profile/tyx)  
![github](icon/github.png) [@tyx](https://github.com/tyx)  
![twitter](icon/twitter.png) [@timbarray](https://twitter.com/timbarray)

![meetup](icon/location.png) [Marseille, France](http://www.meetup.com/afsy-sfpot/events/218685963/) - 27/10/2014

---

## OpenClassrooms : Design Applicatif avec Symfony2 - Zoom sur la Clean Architecture  _<sup>(french)</sup>_

[Slides](http://slideshare.net/RomainKuzniak/design-applicatif-avec-symfony2)  
~~Video~~

By [Romain Kuzniak](https://connect.sensiolabs.com/profile/romainkuzniak)  
![github](icon/github.png) [@romainkuzniak](https://github.com/romainkuzniak)  
![twitter](icon/twitter.png) [@romainkuzniak](https://twitter.com/romainkuzniak)

## Dependency Injection Loves TDD

~~Slides~~  
~~Video~~

By [Marc Morera](https://connect.sensiolabs.com/profile/mmoreram)  
![github](icon/github.png) [@mmoreram](https://github.com/mmoreram)  
![twitter](icon/twitter.png) [@mmoreram](https://twitter.com/mmoreram)

![meetup](icon/location.png) [Paris, France](http://www.meetup.com/afsy-sfpot/events/219062130/) - 12/12/2014

---

## Retour d'experience avec EkinoWordpressBundle sur un site à forte charge _<sup>(french)</sup>_

~~Slides~~  
~~Video~~

By Xavier Coureau

![meetup](icon/location.png) [Lyon, France](http://www.meetup.com/afsy-sfpot/events/219051369/) - 18/12/2014

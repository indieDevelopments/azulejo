Moto: run most of applications powered by MODx on top of Node.js®.

## Intro
It's fun to work with MODx. But the more you dig in, the more you tweak it from inside or write your own versions of modules just cause they don\'t fit. Of course you can contribute to, but popular ones are transfered to paid repos :(

## Problems to solve
Assume that` application is more about data not code. Everything else is optional. So what we'll get:
- Applications lays on data
- Application consists of services
- Services are reusable across applications
- Service consists of modules
- Modules exist either standalone or as a part of a service

## TOC

Azulejo is built on top of awesome [Feathersjs](https://feathersjs.com/), and divided in separate modules:

Module | Purpose
-- | --
[legacy-azulejo-core](https://github.com/indieDevelopments/azulejo-core)| legacy core
[azulejo-core](https://gitlab.com/azulejo/azulejo-core)       | utilities and hooks
[azulejo-backend](https://gitlab.com/azulejo/azulejo-backend) | backend with SSR support
[azulejo-client](https://gitlab.com/azulejo/azulejo-client)   | client application
[azulejo-order](https://gitlab.com/azulejo/azulejo-order)     | order module
`azulejo-man` | db interface

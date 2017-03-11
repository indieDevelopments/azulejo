# Universe

Main purpose is to allow to run any application powered by MODx on top of Node.js.

## Intro
It's fun to work with MODx. But the more you dig in, the more you tweak it from inside or write your own versions of modules. Just cause they don\'t fit. Of course you can contribute to them, but popular ones are transfered to paid repos :( What the purpose to work in ecosystem with weird or paid modules?

## Problems to solve
We assume that the main worth of application is data. Everything else is optional. So what we'll get:
- Same language on backend and frontend
- Same DB to work with
- We can dive deep into opensource world

But we have to write code. That's the price. But we've already paid it a lot.

## What's inside
Universe is built on top of awesome [Feathers](http://feathersjs.com/) (powered by Express), and divided in separate modules:

1. [universe-core](https://github.com/indieDevelopments/universe-core) — contains basic utils and services to work with DB.

2. [universe-module](https://github.com/indieDevelopments/universe-module) — app template which can be used as subapp or as standalone app. It may be a separate API realization, an e-commerce module, etc…

3. [coming soon] universe-space — regular application template in a nutshell.

4. [coming soon] universe-man — app which allows to manage DB data via web-interface




